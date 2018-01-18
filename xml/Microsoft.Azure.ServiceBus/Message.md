<Type Name="Message" FullName="Microsoft.Azure.ServiceBus.Message">
  <TypeSignature Language="C#" Value="public class Message" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Message extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message" />
  <TypeSignature Language="VB.NET" Value="Public Class Message" />
  <TypeSignature Language="F#" Value="type Message = class" />
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
            <span data-ttu-id="e78f9-101">メッセージ オブジェクトを通信し、Service Bus でデータを転送するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-101">The message object used to communicate and transfer data with Service Bus.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e78f9-102">メッセージの構造の詳細については、<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">製品ドキュメント。</a></span><span class="sxs-lookup"><span data-stu-id="e78f9-102">The message structure is discussed in detail in the <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">product documentation.</a></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor" />
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
        <summary>
            <span data-ttu-id="e78f9-103">新しいメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-103">Creates a new Message</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] body);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (body As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Message : byte[] -&gt; Microsoft.Azure.ServiceBus.Message" Usage="new Microsoft.Azure.ServiceBus.Message body" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="array" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="body"><span data-ttu-id="e78f9-104">バイト単位でメッセージのペイロード</span><span class="sxs-lookup"><span data-stu-id="e78f9-104">The payload of the message in bytes</span></span></param>
        <summary>
            <span data-ttu-id="e78f9-105">指定したペイロードから新しいメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-105">Creates a new message from the specified payload.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public byte[] Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As Byte()" />
      <MemberSignature Language="F#" Value="member this.Body : byte[] with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e78f9-106">メッセージの本文を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-106">Gets or sets the body of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e78f9-107">文字列から、新しいメッセージを作成する最も簡単な方法は次のです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-107">The easiest way to create a new message from a string is the following:</span></span>
            <code>
            message.Body = System.Text.Encoding.UTF8.GetBytes("Message1");
            </code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.ServiceBus.Message Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Message" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.ServiceBus.Message" Usage="message.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e78f9-108">既に受信済みメッセージの複製を新しいメッセージとして送信することができるように、メッセージのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-108">Clones a message, so that it is possible to send a clone of an already received message as a new message.</span></span> <span data-ttu-id="e78f9-109">元のメッセージのシステムのプロパティはコピーされません。</span><span class="sxs-lookup"><span data-stu-id="e78f9-109">The system properties of original message are not copied.</span></span></summary>
        <returns><span data-ttu-id="e78f9-110">複製された<see cref="T:Microsoft.Azure.ServiceBus.Message" />です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-110">A cloned <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ContentType" />
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
        <summary><span data-ttu-id="e78f9-111">取得またはコンテンツ tpye 記述子を設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-111">Gets or sets the content tpye descriptor.</span></span></summary>
        <value><span data-ttu-id="e78f9-112">RFC2045 コンテンツの種類の記述子。</span><span class="sxs-lookup"><span data-stu-id="e78f9-112">RFC2045 Content-Type descriptor.</span></span></value>
        <remarks>
              <span data-ttu-id="e78f9-113">必要に応じて RFC2045、セクション 5、たとえば"application/json と"の形式に従って記述子を使用して、メッセージのペイロードを説明します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-113">Optionally describes the payload of the message, with a descriptor following the format of RFC2045, Section 5, for example "application/json".</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.CorrelationId" />
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
        <summary><span data-ttu-id="e78f9-114">取得または設定の相関 id です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-114">Gets or sets the a correlation identifier.</span></span></summary>
        <value><span data-ttu-id="e78f9-115">相関関係の識別子です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-115">Correlation identifier.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-116">により、アプリケーションの例は、返信があった場合に、メッセージの MessageId を反映の相関関係のため、メッセージのコンテキストを指定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-116">Allows an application to specify a context for the message for the purposes of correlation, for example reflecting the MessageId of a message that is being replied to.</span></span>
               <span data-ttu-id="e78f9-117">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a>です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-117">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterErrorDescriptionHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterErrorDescriptionHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterErrorDescriptionHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterErrorDescriptionHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="e78f9-118">エンティティの配信不能サブキューからメッセージを受信すると、詳細なエラーの説明を表すユーザー プロパティのキー。</span><span class="sxs-lookup"><span data-stu-id="e78f9-118">User property key representing detailed error description, when a message is received from a deadletter subqueue of an entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterReasonHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterReasonHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterReasonHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterReasonHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterReasonHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="e78f9-119">エンティティの配信不能サブキューからメッセージが受信したときに、配信不能の理由を表すユーザー プロパティのキーです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-119">User property key representing deadletter reason, when a message is received from a deadletter subqueue of an entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
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
        <summary><span data-ttu-id="e78f9-120">メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-120">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="e78f9-121">メッセージの有効期限刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="e78f9-121">The message expiration time in UTC.</span></span> <span data-ttu-id="e78f9-122">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-122">This property is read-only.</span></span></value>
        <remarks>
             <span data-ttu-id="e78f9-123">有効期限切れが原因でメッセージが削除対象としてマークされ、エンティティから取得できなくなった UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="e78f9-123">The UTC instant at which the message is marked for removal and no longer available for retrieval from the entity due to expiration.</span></span> <span data-ttu-id="e78f9-124">有効期限はによって制御されます、<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />プロパティと、このプロパティから計算<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></span><span class="sxs-lookup"><span data-stu-id="e78f9-124">Expiry is controlled by the <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> property and this property is computed from <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="e78f9-125">場合は、メッセージが受信されていません。</span><span class="sxs-lookup"><span data-stu-id="e78f9-125">If the message has not been received.</span></span> <span data-ttu-id="e78f9-126">たとえばはまだ送信しない場合は、新しいメッセージが作成された場合や受信しています。</span><span class="sxs-lookup"><span data-stu-id="e78f9-126">For example if a new message was created but not yet sent and received.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Label" />
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
        <summary><span data-ttu-id="e78f9-127">取得またはアプリケーション固有のラベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-127">Gets or sets an application specific label.</span></span></summary>
        <value><span data-ttu-id="e78f9-128">アプリケーション固有のラベル</span><span class="sxs-lookup"><span data-stu-id="e78f9-128">The application specific label</span></span></value>
        <remarks>
              <span data-ttu-id="e78f9-129">このプロパティを使用すると、アプリケーションは、電子メールの件名行と同様に標準化された方法でメッセージの目的を受信者に示すことができます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-129">This property enables the application to indicate the purpose of the message to the receiver in a standardized fashion, similar to an email subject line.</span></span> <span data-ttu-id="e78f9-130">マップされた AMQP プロパティは、「件名」です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-130">The mapped AMQP property is "subject".</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.MessageId" />
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
            <span data-ttu-id="e78f9-131">取得またはメッセージを識別するメッセージ Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-131">Gets or sets the MessageId to identify the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
               <span data-ttu-id="e78f9-132">メッセージ識別子は、アプリケーションによって定義される、メッセージとそのペイロードを一意に識別する値です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-132">The message identifier is an application-defined value that uniquely identifies the message and its payload.</span></span> <span data-ttu-id="e78f9-133">この識別子は自由形式の文字列で、GUID またはアプリケーションのコンテキストから派生した識別子を反映することができます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-133">The identifier is a free-form string and can reflect a GUID or an identifier derived from the application context.</span></span> <span data-ttu-id="e78f9-134">有効な場合、<a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">重複検出</a>機能を識別し、2 番目と同じ MessageId とメッセージの転送をさらに削除します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-134">If enabled, the <a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">duplicate detection</a> feature identifies and removes second and further submissions of messages with the same MessageId.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.PartitionKey" />
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
        <summary><span data-ttu-id="e78f9-135">取得またはパーティション分割されたエンティティにメッセージを送信するためのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-135">Gets or sets a partition key for sending a message to a partitioned entity.</span></span></summary>
        <value><span data-ttu-id="e78f9-136">パーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-136">The partition key.</span></span> <span data-ttu-id="e78f9-137">最大長は、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-137">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-138"><a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">パーティション分割されたエンティティ</a>の場合、この値を設定すると、関連するメッセージを同じ内部パーティションに割り当てて、送信順序が正しく記録されるようにできます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-138">For <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">partitioned entities</a>, setting this value enables assigning related messages to the same internal partition, so that submission sequence order is correctly recorded.</span></span> <span data-ttu-id="e78f9-139">パーティションはハッシュ関数でこの値を介して選択され、直接選択することはできません。</span><span class="sxs-lookup"><span data-stu-id="e78f9-139">The partition is chosen by a hash function over this value and cannot be chosen directly.</span></span> <span data-ttu-id="e78f9-140">セッションに対応するエンティティの場合、<see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />プロパティは、この値をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="e78f9-140">For session-aware entities, the <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> property overrides this value.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyTo" />
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
        <summary><span data-ttu-id="e78f9-141">取得または応答を送信するエンティティのアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-141">Gets or sets the address of an entity to send replies to.</span></span></summary>
        <value><span data-ttu-id="e78f9-142">返信先エンティティのアドレス。</span><span class="sxs-lookup"><span data-stu-id="e78f9-142">The reply entity address.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-143">これはアプリケーションによって定義される省略可能な値であり、メッセージの受信者への応答パスを表す標準的な方法です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-143">This optional and application-defined value is a standard way to express a reply path to the receiver of the message.</span></span> <span data-ttu-id="e78f9-144">応答が必要な場合、送信者は、この値を応答の送信先にするキューまたはトピックの絶対または相対パスに設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-144">When a sender expects a reply, it sets the value to the absolute or relative path of the queue or topic it expects the reply to be sent to.</span></span>
               <span data-ttu-id="e78f9-145">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a>です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-145">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
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
        <summary><span data-ttu-id="e78f9-146">取得または設定のセッションの識別子の拡張、<see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />アドレス。</span><span class="sxs-lookup"><span data-stu-id="e78f9-146">Gets or sets a session identifier augmenting the <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" /> address.</span></span></summary>
        <value><span data-ttu-id="e78f9-147">セッションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-147">Session identifier.</span></span> <span data-ttu-id="e78f9-148">最大長は、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-148">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-149">この値は、ReplyTo 情報を拡張しの応答を返信エンティティに送信されるときに設定されているセッション Id を指定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-149">This value augments the ReplyTo information and specifies which SessionId should be set for the reply when sent to the reply entity.</span></span> <span data-ttu-id="e78f9-150">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a></span><span class="sxs-lookup"><span data-stu-id="e78f9-150">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
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
        <summary><span data-ttu-id="e78f9-151">取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-151">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span> <span data-ttu-id="e78f9-152">このプロパティは、UTC 時刻を返しますプロパティを設定するときに指定された DateTime 値もあります (utc)。</span><span class="sxs-lookup"><span data-stu-id="e78f9-152">This property returns the time in UTC; when setting the property, the supplied DateTime value must also be in UTC.</span></span></summary>
        <value><span data-ttu-id="e78f9-153">スケジュールされたエンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="e78f9-153">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="e78f9-154">この値では、遅延メッセージを送信するためです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-154">This value is for delayed message sending.</span></span>
            <span data-ttu-id="e78f9-155">後で、特定の時刻に送信するメッセージを遅延することを利用します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-155">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks> <span data-ttu-id="e78f9-156">メッセージがエンキュー時間では、メッセージを同時に送信されることは限りません。</span><span class="sxs-lookup"><span data-stu-id="e78f9-156">Message enqueuing time does not mean that the message will be sent at the same time.</span></span> <span data-ttu-id="e78f9-157">にキュー入れられたが取得されますが、実際の送信時間は、キューの作業負荷とその状態によって異なります。</span><span class="sxs-lookup"><span data-stu-id="e78f9-157">It will get enqueued, but the actual sending time depends on the queue's workload and its state.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.SessionId" />
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
        <summary><span data-ttu-id="e78f9-158">取得またはセッションに対応するエンティティのセッション識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-158">Gets or sets the session identifier for a session-aware entity.</span></span></summary>
        <value><span data-ttu-id="e78f9-159">セッション識別子。</span><span class="sxs-lookup"><span data-stu-id="e78f9-159">The session identifier.</span></span> <span data-ttu-id="e78f9-160">最大長は、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-160">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-161">この値はアプリケーションによって定義され、セッションを認識するエンティティの場合に、メッセージのセッションへの所属を指定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-161">For session-aware entities, this application-defined value specifies the session affiliation of the message.</span></span> <span data-ttu-id="e78f9-162">同じセッション識別子を持つメッセージがまとめてロックされ、正確な順序での処理と多重化が可能になります。</span><span class="sxs-lookup"><span data-stu-id="e78f9-162">Messages with the same session identifier are subject to summary locking and enable exact in-order processing and demultiplexing.</span></span> <span data-ttu-id="e78f9-163">セッションを認識しないエンティティの場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-163">For session-unaware entities, this value is ignored.</span></span>
               <span data-ttu-id="e78f9-164">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">メッセージ セッション</a>です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-164">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">Message Sessions</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.Azure.ServiceBus.Message.Size" />
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
        <summary>
            <span data-ttu-id="e78f9-165">メッセージ本文の合計サイズをバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-165">Gets the total size of the message body in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.Message/SystemPropertiesCollection SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As Message.SystemPropertiesCollection" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" Usage="Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e78f9-166">取得、 <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />、システムによって設定されているプロパティの格納に使用されます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-166">Gets the <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />, which is used to store properties that are set by the system.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e78f9-167">取得またはメッセージの「有効期限の時間」の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-167">Gets or sets the message’s "time to live" value.</span></span> 
            </summary>
        <value><span data-ttu-id="e78f9-168">有効期限値、メッセージの時刻。</span><span class="sxs-lookup"><span data-stu-id="e78f9-168">The message’s time to live value.</span></span></value>
        <remarks>
                <span data-ttu-id="e78f9-169">この値は、メッセージの有効期限が切れるまでの相対期間は、メッセージの開始時点から開始がされて受け入れにキャプチャされるように、ブローカーによって格納されている<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-169">This value is the relative duration after which the message expires, starting from the instant the message has been accepted and stored by the broker, as captured in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />.</span></span> <span data-ttu-id="e78f9-170">ときに明示的に設定せず、想定した値は、それぞれのキューまたはトピックの DefaultTimeToLive です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-170">When not set explicitly, the assumed value is the DefaultTimeToLive for the respective queue or topic.</span></span> <span data-ttu-id="e78f9-171">メッセージ レベル<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />値は、エンティティの DefaultTimeToLive 設定より長くすることはできませんし、それの場合は自動的に調整します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-171">A message-level <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> value cannot be longer than the entity's DefaultTimeToLive setting and it is silently adjusted if it does.</span></span> <span data-ttu-id="e78f9-172">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">有効期限</a></span><span class="sxs-lookup"><span data-stu-id="e78f9-172">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">Expiration</a></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.To" />
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
        <summary><span data-ttu-id="e78f9-173">取得または「を」アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-173">Gets or sets the "to" address.</span></span></summary>
        <value><span data-ttu-id="e78f9-174">「を」のアドレス。</span><span class="sxs-lookup"><span data-stu-id="e78f9-174">The "to" address.</span></span></value>
        <remarks>
               <span data-ttu-id="e78f9-175">このプロパティはルーティング　シナリオでの将来の使用のために予約されており、現在はブローカー自体で無視されます。</span><span class="sxs-lookup"><span data-stu-id="e78f9-175">This property is reserved for future use in routing scenarios and presently ignored by the broker itself.</span></span> <span data-ttu-id="e78f9-176">アプリケーションは、この値を使用してルール主導で<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">自動順行連鎖</a>メッセージの目的の論理送信先を指定するシナリオです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-176">Applications can use this value in rule-driven <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">auto-forward chaining</a> scenarios to indicate the intended logical destination of the message.</span></span>
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="message.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e78f9-177">現在のメッセージを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-177">Returns a string that represents the current message.</span></span></summary>
        <returns><span data-ttu-id="e78f9-178">現在のメッセージの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="e78f9-178">The string representation of the current message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; UserProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; UserProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.UserProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e78f9-179">カスタム メッセージのメタデータを使用できる ユーザーのプロパティ"バッグを取得します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-179">Gets the "user properties" bag, which can be used for custom message metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e78f9-180">次の値のみの種類がサポートされて: byte、sbyte、char、short、ushort、int、uint、long、ulong、float、double、decimal、bool、Guid、文字列、Uri、DateTime、DateTimeOffset、TimeSpan、ストリーム、byte[]、および IList の IDictionary には、種類がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e78f9-180">Only following value types are supported: byte, sbyte, char, short, ushort, int, uint, long, ulong, float, double, decimal, bool, Guid, string, Uri, DateTime, DateTimeOffset, TimeSpan, Stream, byte[], and IList / IDictionary of supported types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
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
        <summary><span data-ttu-id="e78f9-181">取得またはパーティションの転送キュー経由でのエンティティにメッセージを送信するためのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="e78f9-181">Gets or sets a partition key for sending a message into an entity via a partitioned transfer queue.</span></span></summary>
        <value><span data-ttu-id="e78f9-182">パーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="e78f9-182">The partition key.</span></span> <span data-ttu-id="e78f9-183">最大長は、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-183">Maximum length is 128 characters.</span></span> </value>
        <remarks>
               <span data-ttu-id="e78f9-184">この値が転送キュー パーティションを選択して、トランザクションのスコープ内の転送キュー経由でメッセージを送信する場合: これは機能的に等価<see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" />してメッセージに格納されている同時に、順序で転送されるようになります。</span><span class="sxs-lookup"><span data-stu-id="e78f9-184">If a message is sent via a transfer queue in the scope of a transaction, this value selects the transfer queue partition: This is functionally equivalent to <see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" /> and ensures that messages are kept together and in order as they are transferred.</span></span>
               <span data-ttu-id="e78f9-185">参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">転送し、経由で送信</a>です。</span><span class="sxs-lookup"><span data-stu-id="e78f9-185">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">Transfers and Send Via</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
  </Members>
</Type>