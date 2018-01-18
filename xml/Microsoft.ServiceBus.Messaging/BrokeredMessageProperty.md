<Type Name="BrokeredMessageProperty" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessageProperty : System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessageProperty extends System.Object implements class System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessageProperty&#xA;Implements IMessageProperty" />
  <TypeSignature Language="F#" Value="type BrokeredMessageProperty = class&#xA;    interface IMessageProperty" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IMessageProperty</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="e03dc-101">プロパティ バッグを表す、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-101">Represents the property bag for a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessageProperty ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e03dc-102"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-103">取得またはコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-103">Gets or sets the type of the content.</span></span></summary>
        <value><span data-ttu-id="e03dc-104">メッセージ本文のコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="e03dc-104">The type of the content of the message body.</span></span> <span data-ttu-id="e03dc-105">これは、送信者と受信者のアプリケーション固有のロジックで使用されるコンテンツの種類の識別子です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-105">This is a content type identifier utilized by the sender and receiver for application specific logic.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-106">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-106">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-107">取得または設定の相関関係の識別子。</span><span class="sxs-lookup"><span data-stu-id="e03dc-107">Gets or sets the identifier of the correlation.</span></span></summary>
        <value><span data-ttu-id="e03dc-108">相関関係の識別子です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-108">The correlation identifier.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-109">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-109">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-110">このメッセージの配信に加えられた配信の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-110">Gets the number of deliveries that have been made to deliver this message.</span></span></summary>
        <value><span data-ttu-id="e03dc-111">このメッセージの配信に加えられた配送の数。</span><span class="sxs-lookup"><span data-stu-id="e03dc-111">The number of deliveries that have been made to deliver this message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-112">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-112">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="e03dc-113">ServiceBus によってメッセージが配信されていない場合。</span><span class="sxs-lookup"><span data-stu-id="e03dc-113">If the message has not been delivered by ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-114">取得または送信時刻の日時を UTC に設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-114">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="e03dc-115">エンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="e03dc-115">The enqueue time in UTC.</span></span> <span data-ttu-id="e03dc-116">この値は、メッセージをエンキューの実際の時間を表します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-116">This value represents the actual time of enqueuing the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-117">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-117">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-118">メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-118">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="e03dc-119">メッセージの有効期限刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="e03dc-119">The message expiration time in UTC.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-120">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-120">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-121">取得またはこのプロパティを永続化を強制するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-121">Gets or sets whether to force persistence on this property.</span></span></summary>
        <value><span data-ttu-id="e03dc-122">このプロパティに永続化を強制する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-122">true to force persistence on this property; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-123">取得またはアプリケーション固有のラベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-123">Gets or sets the application specific label.</span></span></summary>
        <value><span data-ttu-id="e03dc-124">アプリケーション固有のラベル。</span><span class="sxs-lookup"><span data-stu-id="e03dc-124">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-125">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-125">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-126">キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-126">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="e03dc-127">日時キュー/サブスクリプションになるまで、メッセージがロックされます。</span><span class="sxs-lookup"><span data-stu-id="e03dc-127">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-128">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-128">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="e03dc-129">場合は、ServiceBus からメッセージを受信しませんでした。</span><span class="sxs-lookup"><span data-stu-id="e03dc-129">If the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-130">Service Bus によってメッセージに割り当てられたロック トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-130">Gets the lock token assigned by Service Bus to the message.</span></span></summary>
        <value><span data-ttu-id="e03dc-131">Service Bus によってメッセージに割り当てられたロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="e03dc-131">The lock token assigned by Service Bus to the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-132">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-132">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="e03dc-133">場合は、ServiceBus からメッセージを受信しませんでした。</span><span class="sxs-lookup"><span data-stu-id="e03dc-133">If the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-134">仲介型メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-134">Gets the brokered message.</span></span></summary>
        <value><span data-ttu-id="e03dc-135">仲介型メッセージ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e03dc-135">The brokered message object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-136">取得またはメッセージの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-136">Gets or sets the identifier of the message.</span></span></summary>
        <value><span data-ttu-id="e03dc-137">メッセージ ID。</span><span class="sxs-lookup"><span data-stu-id="e03dc-137">The message identifier.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-138">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-138">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="e03dc-139">場合はメッセージ id が null であるか、長さは 128 文字を超えています。</span><span class="sxs-lookup"><span data-stu-id="e03dc-139">If message identifier is null or exceeds 128 characters in length.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public static readonly string Name;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Name" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Name As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Name : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e03dc-140">プロパティ バッグを適用するために使用される名前、<see cref="T:System.ServiceModel.Channels.Message" />メッセージを送信するときにします。</span><span class="sxs-lookup"><span data-stu-id="e03dc-140">The name used for applying the property bag to a <see cref="T:System.ServiceModel.Channels.Message" /> when sending a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-141">取得または設定に、キューまたはトピックをセッション対応していないトランザクション メッセージを送信するためのパーティション キー。</span><span class="sxs-lookup"><span data-stu-id="e03dc-141">Gets or sets a partition key for sending a transactional message to a queue or topic that is not session-aware.</span></span></summary>
        <value><span data-ttu-id="e03dc-142"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-142">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-143">仲介型メッセージのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-143">Gets the properties of the brokered message.</span></span></summary>
        <value><span data-ttu-id="e03dc-144">仲介型メッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="e03dc-144">The properties of the brokered message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-145">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-145">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-146">取得またはに返信するキューのアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-146">Gets or sets the address of the queue to reply to.</span></span></summary>
        <value><span data-ttu-id="e03dc-147">メッセージ キューのアドレスに返信します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-147">The reply to queue address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-148">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-148">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-149">取得または設定に返信するセッション識別子。</span><span class="sxs-lookup"><span data-stu-id="e03dc-149">Gets or sets the session identifier to reply to.</span></span></summary>
        <value><span data-ttu-id="e03dc-150">返信するセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-150">The session identifier to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-151">取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-151">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span></summary>
        <value><span data-ttu-id="e03dc-152">スケジュールされたエンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="e03dc-152">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="e03dc-153">この値では、遅延メッセージを送信するためです。</span><span class="sxs-lookup"><span data-stu-id="e03dc-153">This value is for delayed message sending.</span></span> <span data-ttu-id="e03dc-154">後で、特定の時刻に送信するメッセージを遅延することを利用します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-154">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-155">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-155">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e03dc-156">渡された値が場合 DateTime.MaxValue します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-156">If the passed in value is DateTime.MaxValue.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-157">Service Bus によってメッセージに割り当てられた一意の番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-157">Gets the unique number assigned to a message by the Service Bus.</span></span></summary>
        <value><span data-ttu-id="e03dc-158">Service Bus によってメッセージに割り当てられた一意の番号。</span><span class="sxs-lookup"><span data-stu-id="e03dc-158">The unique number assigned to a message by the Service Bus.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-159">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-159">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="e03dc-160">場合は、メッセージがメッセージ サーバーから受信しませんでした。</span><span class="sxs-lookup"><span data-stu-id="e03dc-160">If the message was not received from the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-161">取得またはセッションの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-161">Gets or sets the identifier of the session.</span></span></summary>
        <value><span data-ttu-id="e03dc-162">セッションの識別子。</span><span class="sxs-lookup"><span data-stu-id="e03dc-162">The identifier of the session.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-163">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-163">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IMessageProperty.CreateCopy">
      <MemberSignature Language="C#" Value="System.ServiceModel.Channels.IMessageProperty IMessageProperty.CreateCopy ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.ServiceModel.Channels.IMessageProperty System.ServiceModel.Channels.IMessageProperty.CreateCopy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.System#ServiceModel#Channels#IMessageProperty#CreateCopy" />
      <MemberSignature Language="VB.NET" Value="Function CreateCopy () As IMessageProperty Implements IMessageProperty.CreateCopy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.IMessageProperty.CreateCopy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IMessageProperty</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-164">取得または有効期限値、メッセージの時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-164">Gets or sets the message’s time to live value.</span></span> <span data-ttu-id="e03dc-165">その後、メッセージは期限切れから開始その TimeToLive の値が有効期限が切れるし、メッセージ ストアに保持されなくよりも古いサービス Bus.Messages にメッセージが送信される期間です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-165">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="e03dc-166">サブスクライバーは期限切れのメッセージを受信することができません。</span><span class="sxs-lookup"><span data-stu-id="e03dc-166">Subscribers will be unable to receive expired messages.</span></span></summary>
        <value><span data-ttu-id="e03dc-167">有効期限値、メッセージの時刻。</span><span class="sxs-lookup"><span data-stu-id="e03dc-167">The message’s time to live value.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-168">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-168">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e03dc-169">渡された値が TimeSpan.Zero 小さい場合。</span><span class="sxs-lookup"><span data-stu-id="e03dc-169">If the passed in value is less than or equal to TimeSpan.Zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-170">取得または送信をアドレスに設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-170">Gets or sets the send to address.</span></span></summary>
        <value><span data-ttu-id="e03dc-171">送信先キューのアドレス。</span><span class="sxs-lookup"><span data-stu-id="e03dc-171">The address of the destination queue.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="e03dc-172">場合は、メッセージは破棄された状態です。</span><span class="sxs-lookup"><span data-stu-id="e03dc-172">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e03dc-173">取得またはトランザクションがある場合、転送キュー経由のメッセージを送信するために、パーティション キー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-173">Gets or sets a partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></summary>
        <value><span data-ttu-id="e03dc-174"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="e03dc-174">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>