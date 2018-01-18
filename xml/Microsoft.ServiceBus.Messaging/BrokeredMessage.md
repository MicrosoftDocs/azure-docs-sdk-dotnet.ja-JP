<Type Name="BrokeredMessage" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessage">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessage : IDisposable, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessage extends System.Object implements class System.IDisposable, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessage&#xA;Implements IDisposable, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type BrokeredMessage = class&#xA;    interface IXmlSerializable&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("BrokeredMessage", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="6dd2c-101">Service Bus クライアント間の通信の単位を表します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-101">Represents the unit of communication between Service Bus clients.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6dd2c-102"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage messageBodyStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream"><span data-ttu-id="6dd2c-103">メッセージのボディ ストリーム。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-103">The message body stream.</span></span></param>
        <summary><span data-ttu-id="6dd2c-104"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage serializableObject" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="serializableObject"><span data-ttu-id="6dd2c-105">メッセージ本文にシリアル化されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-105">The object to be serialized into the message body.</span></span></param>
        <summary><span data-ttu-id="6dd2c-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />バイナリ XmlDictionaryWriter に DataContractSerializer を使用して、指定されたオブジェクトからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class from a given object by using DataContractSerializer with a binary XmlDictionaryWriter.</span></span></summary>
        <remarks><span data-ttu-id="6dd2c-107">既定の<see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" />オブジェクトをシリアル化するために使用します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-107">A default <see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" /> is used for serializing the object.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream, bool ownsStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream, bool ownsStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream, ownsStream As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream * bool -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (messageBodyStream, ownsStream)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
        <Parameter Name="ownsStream" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream"><span data-ttu-id="6dd2c-108">メッセージのボディ ストリーム。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-108">The message body stream.</span></span></param>
        <param name="ownsStream"><span data-ttu-id="6dd2c-109">メッセージの終了時に、ストリームは閉じられますことを指定する場合は trueメッセージが閉じられたときに、ストリームは削除されないことを示すために false になります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-109">true to indicate that the stream will be closed when the message is closed; false to indicate that the stream will not be closed when the message is closed.</span></span></param>
        <summary><span data-ttu-id="6dd2c-110">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />クラス、本文として提供されたストリームを使用します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class using the supplied stream as its body.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (serializableObject, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="serializableObject"> <span data-ttu-id="6dd2c-111">シリアル化可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-111">The serializable object.</span></span> </param>
        <param name="serializer">         <span data-ttu-id="6dd2c-112">シリアライザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-112">The serializer object.</span></span> </param>
        <summary> <span data-ttu-id="6dd2c-113">指定された XmlObjectSerializer を使用して、指定されたオブジェクトから BrokeredMessage を作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="6dd2c-113">Constructor that creates a BrokeredMessage from a given object using the provided XmlObjectSerializer</span></span> </summary>
        <remarks> <span data-ttu-id="6dd2c-114">例外の指定されたシリアライザーがスローおよび適切なアクションを実行できますの注意する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-114">You should be aware of the exceptions that their provided Serializer can throw and take appropriate actions.</span></span> <span data-ttu-id="6dd2c-115">参照してください<see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" />例外とその原因の可能な一覧についてはします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-115">Please refer to <see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" /> for a possible list of exceptions and their cause.</span></span> </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6dd2c-116">Null のシリアライザーが null でない serializableObject でメソッドに渡された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-116">Thrown when null serializer is passed to the method with a non-null serializableObject</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon ()" />
      <MemberSignature Language="F#" Value="member this.Abandon : unit -&gt; unit" Usage="brokeredMessage.Abandon " />
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
        <summary><span data-ttu-id="6dd2c-117">ピーク ロックのメッセージのロックを破棄します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-117">Abandons the lock on a peek-locked message.</span></span></summary>
        <remarks> <span data-ttu-id="6dd2c-118">この操作は、ピーク ロックのモードで受信したメッセージのみ実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-118">This operation should only be exercised on a message received in peek-lock mode.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-119">破棄された状態では、メッセージまたはメッセージを受信した受信側が破棄された状態では場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-119">Thrown when the message is in the disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-120">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-120">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6dd2c-121">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-121">Thrown when operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="6dd2c-122">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-122">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="6dd2c-123">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-123">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="6dd2c-124">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-124">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="6dd2c-125">メッセージング エンティティのメッセージを受信しましたが削除されました。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-125">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="6dd2c-126">ロックに関連付けられているときに、このメッセージが失われたまたはロック トークンが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-126">When the lock associated with this message was lost or the lock token was not found.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="6dd2c-127">ときにこのメッセージが、セッションとセッションに関連付けられているロックから受け取りました。 が失われました。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-127">When this message was received from a Session and the lock associated with the session was lost.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="6dd2c-128">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-128">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="6dd2c-129">ときにエンティティへの同時接続の数が最大許容値を超えています。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-129">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Abandon : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Abandon propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-130">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-130">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-131">ピーク ロックのメッセージのロックを破棄します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-131">Abandons the lock on a peek-locked message.</span></span></summary>
        <remarks> <span data-ttu-id="6dd2c-132">この操作は、ピーク ロックのモードで受信したメッセージのみ実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-132">This operation should only be exercised on a message received in peek-lock mode.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-133">場合にスローされる<list type="bullet"><item>メッセージは破棄された状態にします</item>。<item>受信側がメッセージを受信しましたが、破棄された状態</item></list></span><span class="sxs-lookup"><span data-stu-id="6dd2c-133">Thrown when <list type="bullet"><item>message is in disposed state.</item><item>the receiver with which the messsage was received is in disposed state</item></list></span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-134">場合にスローされる<list type="bullet"><item>がメッセージ サーバーから受信されていないメッセージで呼び出されます</item>。<item>がピーク ロックのモードで受信されていないメッセージで呼び出されます</item></list></span><span class="sxs-lookup"><span data-stu-id="6dd2c-134">Thrown when <list type="bullet"><item>invoked on a message that has not been received from the message server.</item><item>invoked on a message that has not been received in peek-lock mode</item></list></span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6dd2c-135">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-135">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="6dd2c-136">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-136">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span>
                                            <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.ServiceModel.CommunicationException"><span data-ttu-id="6dd2c-137">キューまたはサブスクリプションから受信したメッセージは既に存在しないメッセージ サーバーの場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-137">Thrown when the queue or subscription that the message was received from is no longer present in the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync " />
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
        <summary><span data-ttu-id="6dd2c-138">ピーク ロックのメッセージのロックを非同期的に中止します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-138">Asynchronously abandons the lock on a peek-locked message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-139">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-139">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-140">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-140">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-141">ピーク ロックのメッセージのロックを非同期的に中止します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-141">Asynchronously abandons the lock on a peek-locked message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-142">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-142">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="brokeredMessage.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6dd2c-143">新しいメッセージとしてメッセージの複製を送信することができるように、メッセージを複製します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-143">Clones a message, so that it is possible to send a clone of a message as a new message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-144"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />クローンとして作成されたメッセージを格納しています。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-144">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that contains the cloned message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Complete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Complete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete ()" />
      <MemberSignature Language="F#" Value="member this.Complete : unit -&gt; unit" Usage="brokeredMessage.Complete " />
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
        <summary><span data-ttu-id="6dd2c-145">メッセージの受信操作が完了したことを示し、メッセージは、処理済みとマークする必要があります、削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-145">Completes the receive operation of a message and indicates that the message should be marked as processed and deleted.</span></span></summary>
        <remarks> <span data-ttu-id="6dd2c-146">このメソッドは、メッセージの確実な配信の受信機と Service Bus との間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-146">This method is used as a handshake between the receiver and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="6dd2c-147">このメソッドを呼び出す前に、受信側に失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-147">If the receiver failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-148">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-148">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-149">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-149">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="6dd2c-150">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-150">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6dd2c-151">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-151">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="6dd2c-152">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-152">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="6dd2c-153">メッセージのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-153">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="6dd2c-154">LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-154">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="6dd2c-155">セッションのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-155">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="6dd2c-156">セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-156">The session lock duration is the same as the message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="6dd2c-157">初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-157">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="6dd2c-158">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-158">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="6dd2c-159">メッセージング エンティティのメッセージを受信しましたが削除されました。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-159">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="6dd2c-160">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-160">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="6dd2c-161">ときにエンティティへの同時接続の数が最大許容値を超えています。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-161">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.CompleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.CompleteAsync " />
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
        <summary><span data-ttu-id="6dd2c-162">非同期的にメッセージの受信操作が完了したことを示し、メッセージは、処理済みとマークする必要があります、削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-162">Asynchronously completes the receive operation of a message and indicates that the message should be marked as processed and deleted.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-163">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-163">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-164">取得またはコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-164">Gets or sets the type of the content.</span></span></summary>
        <value><span data-ttu-id="6dd2c-165">メッセージ本文のコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-165">The type of the content of the message body.</span></span> <span data-ttu-id="6dd2c-166">これは、送信者と受信者のアプリケーション固有のロジックで使用されるコンテンツの種類の識別子です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-166">This is a content type identifier utilized by the sender and receiver for application specific logic.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-167">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-167">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-168">取得または設定の相関関係の識別子。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-168">Gets or sets the identifier of the correlation.</span></span></summary>
        <value><span data-ttu-id="6dd2c-169">相関関係の識別子。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-169">The identifier of the correlation.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-170">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-170">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter ()" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : unit -&gt; unit" Usage="brokeredMessage.DeadLetter " />
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
        <summary><span data-ttu-id="6dd2c-171">配信不能キューにメッセージを移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-171">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-172">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-172">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-173">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-173">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.DeadLetter propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-174">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-174">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-175">配信不能キューにメッセージを移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-175">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : string * string -&gt; unit" Usage="brokeredMessage.DeadLetter (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason"><span data-ttu-id="6dd2c-176">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-176">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="6dd2c-177">メッセージの配信不能の説明情報。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-177">The description information for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="6dd2c-178">配信不能キューにメッセージを移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-178">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-179">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-179">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-180">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-180">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:System.ServiceModel.CommunicationException"><span data-ttu-id="6dd2c-181">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-181">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6dd2c-182">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-182">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="6dd2c-183">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-183">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="6dd2c-184">メッセージのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-184">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="6dd2c-185">LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-185">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for Queues and Subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="6dd2c-186">セッションのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-186">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="6dd2c-187">セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-187">Session lock duration is the same as message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="6dd2c-188">初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-188">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for Queues and Subscriptions respectively.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync " />
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
        <summary><span data-ttu-id="6dd2c-189">非同期的にメッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-189">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-190">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-190">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-191">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-191">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-192">非同期的にメッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-192">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-193">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-193">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason"><span data-ttu-id="6dd2c-194">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-194">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="6dd2c-195">メッセージの配信不能の説明情報。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-195">The description information for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="6dd2c-196">非同期的にメッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-196">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-197">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-197">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer ()" />
      <MemberSignature Language="F#" Value="member this.Defer : unit -&gt; unit" Usage="brokeredMessage.Defer " />
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
        <summary><span data-ttu-id="6dd2c-198">受信側がこのメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-198">Indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <remarks><span data-ttu-id="6dd2c-199">メッセージを保留する前にユーザーは、後で検索できるメッセージの受信確認を確保する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-199">Before deferring the message, user MUST set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-200">破棄された状態では、メッセージまたはメッセージを受信した受信側が破棄された状態では場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-200">Thrown when the message is in the disposed state or the receiver with which the message was received is in the disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-201">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-201">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="6dd2c-202">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-202">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6dd2c-203">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-203">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="6dd2c-204">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-204">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="6dd2c-205">メッセージのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-205">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="6dd2c-206">LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-206">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="6dd2c-207">セッションのロックの有効期限が切れた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-207">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="6dd2c-208">セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-208">The session lock duration is the same as the message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="6dd2c-209">初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-209">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="6dd2c-210">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-210">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="6dd2c-211">メッセージング エンティティのメッセージを受信しましたが削除されました。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-211">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="6dd2c-212">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-212">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="6dd2c-213">ときにエンティティへの同時接続の数が最大許容値を超えています。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-213">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Defer : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Defer propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-214">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-214">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-215">受信側がこのメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-215">Indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <remarks><span data-ttu-id="6dd2c-216">メッセージを保留する前にユーザーは、後で検索できるメッセージの受信確認を確保する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-216">Before deferring the message, user MUST set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync " />
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
        <summary><span data-ttu-id="6dd2c-217">非同期的に受信側がこのメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-217">Asynchronously indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-218">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-218">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="6dd2c-219">変更するプロパティのキー/値ペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-219">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="6dd2c-220">非同期的に受信側がこのメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-220">Asynchronously indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-221">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-221">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-222">配信の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-222">Gets the number of deliveries.</span></span></summary>
        <value><span data-ttu-id="6dd2c-223">配信したファイルの数。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-223">The number of deliveries.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-224">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-224">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-225">ServiceBus によってメッセージが配信されていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-225">Thrown if the message has not been delivered by ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="brokeredMessage.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6dd2c-226">アンマネージ リソースの解放またはリセットに関連付けられているアプリケーション定義のタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-226">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-227">取得またはメッセージのエンキューされたシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-227">Gets or sets the enqueued sequence number of the message.</span></span></summary>
        <value><span data-ttu-id="6dd2c-228">メッセージのエンキューされたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-228">The enqueued sequence number of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-229">取得または送信時刻の日時を UTC に設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-229">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="6dd2c-230">エンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-230">The enqueue time in UTC.</span></span> <span data-ttu-id="6dd2c-231">この値は、メッセージをエンキューの実際の時間を表します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-231">This value represents the actual time of enqueuing the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-232">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-232">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-233">メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-233">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="6dd2c-234">メッセージの有効期限刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-234">The message expiration time in UTC.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-235">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-235">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-236">場合は ServerBus によってメッセージが配信されていません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-236">If the message has not been delivered by ServerBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-237">取得またはメッセージがしばらくの間のメモリ内に保持されているのではなく、すぐに、データベースに永続化されるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-237">Gets or sets a value that indicates whether the message is to be persisted to the database immediately, instead of being held in memory for a short time.</span></span> <span data-ttu-id="6dd2c-238">Express 以外のキューまたはトピックにメッセージが送信された場合、このプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-238">This property is ignored if the message is sent to a non-express queue or topic.</span></span></summary>
        <value><span data-ttu-id="6dd2c-239">メッセージが短い時間です。 メモリ内に保持されているのではなく、すぐにデータベースに永続化する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-239">true if the message is to be persisted to the database immediately, instead of being held in memory for a short time; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : unit -&gt; 'T" Usage="brokeredMessage.GetBody " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="6dd2c-240">メッセージの本文を逆シリアル化する型。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-240">The type to which the message body will be deserialized.</span></span></typeparam>
        <summary><span data-ttu-id="6dd2c-241">使用して、指定した型のオブジェクトに、仲介型メッセージの本文を逆シリアル化、 <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> 、バイナリと<see cref="T:System.Xml.XmlDictionaryReader" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-241">Deserializes the brokered message body into an object of the specified type by using the <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> with a binary <see cref="T:System.Xml.XmlDictionaryReader" />.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-242">逆シリアル化されたオブジェクト、またはグラフ。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-242">The deserialized object or graph.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-243">メッセージが破棄されている場合状態や、メッセージ ボディ ストリームは既に破棄されています。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-243">If the message is in disposed state or the message body stream is already disposed.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-244">ボディ ストリームには、データがないか、メッセージ本文が含まれています。 メッセージには、null のボディ ストリームが含まれている場合は既に使用済みです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-244">If the message contains a null body stream or the body stream contains no data or the message body has already been consumed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; (System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;(class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1(System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) (serializer As XmlObjectSerializer) As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="brokeredMessage.GetBody serializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T"> <span data-ttu-id="6dd2c-245">ジェネリック型パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-245">Generic type parameter.</span></span> </typeparam>
        <param name="serializer"> <span data-ttu-id="6dd2c-246">シリアライザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-246">The serializer object.</span></span> </param>
        <summary><span data-ttu-id="6dd2c-247">バイナリ XmlObjectSerializer に DataContractSerializer を使用して、指定した型のオブジェクトには、BrokeredMessage の本文を逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-247">Deserializes the BrokeredMessage body into an object of the specified type using DataContractSerializer with a Binary XmlObjectSerializer.</span></span> </summary>
        <returns> <span data-ttu-id="6dd2c-248">逆シリアル化されたオブジェクト/グラフ</span><span class="sxs-lookup"><span data-stu-id="6dd2c-248">The deserialized object/graph</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"> <span data-ttu-id="6dd2c-249">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-249">Thrown if the message is in disposed state.</span></span> </exception>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="6dd2c-250">Null シリアライザー オブジェクトで呼び出されたときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-250">Thrown when invoked with a Null serializer object.</span></span> </exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="6dd2c-251">メッセージには、Null 本文ストリームが含まれている場合にスローされます、データが含まれていない、または 1 回 (GetBody() 呼び出し) を介して、ストリームが読み取られた場合。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-251">Thrown if the message contains a Null body stream, contains no data, or if the stream has been read once (through any GetBody() calls).</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="IsBodyConsumed">
      <MemberSignature Language="C#" Value="public bool IsBodyConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBodyConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBodyConsumed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBodyConsumed : bool" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-252">メッセージが使用されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-252">Specifies whether the message has been consumed.</span></span></summary>
        <value><span data-ttu-id="6dd2c-253">メッセージが使用された場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-253">true if the message has been consumed; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-254">取得またはアプリケーション固有のラベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-254">Gets or sets the application specific label.</span></span></summary>
        <value><span data-ttu-id="6dd2c-255">アプリケーション固有のラベル。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-255">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-256">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-256">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-257">キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-257">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="6dd2c-258">日時キュー/サブスクリプションになるまで、メッセージがロックされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-258">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-259">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-259">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-260">ServiceBus から、メッセージが受信されなかった場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-260">Thrown if the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-261">Service Bus によってこのメッセージに割り当てられたロック トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-261">Gets the lock token assigned by Service Bus to this message.</span></span></summary>
        <value><span data-ttu-id="6dd2c-262">Service Bus によってこのメッセージに割り当てられたロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-262">The lock token assigned by Service Bus to this message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-263">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-263">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-264">ServiceBus から、メッセージが受信されなかった場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-264">Thrown if the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-265">取得またはメッセージの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-265">Gets or sets the identifier of the message.</span></span> <span data-ttu-id="6dd2c-266">これは、有効になっている場合、Service Bus がメッセージの重複の識別に使用できるユーザー定義の値です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-266">This is a user-defined value that Service Bus can use to identify duplicate messages, if enabled.</span></span></summary>
        <value><span data-ttu-id="6dd2c-267">メッセージの識別子。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-267">The identifier of the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-268">メッセージが破棄された状態の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-268">Thrown if the message is in a disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="6dd2c-269">メッセージ id が null または長さは 128 文字を超える場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-269">Thrown if the message identifier is null or exceeds 128 characters in length.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-270">取得または設定に、キューまたはトピックをセッション対応していないトランザクション メッセージを送信するためのパーティション キー。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-270">Gets or sets a partition key for sending a transactional message to a queue or topic that is not session-aware.</span></span></summary>
        <value><span data-ttu-id="6dd2c-271">トランザクション メッセージを送信するためのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-271">The partition key for sending a transactional message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-272">アプリケーションの特定のメッセージ プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-272">Gets the application specific message properties.</span></span></summary>
        <value><span data-ttu-id="6dd2c-273">アプリケーションの特定のメッセージ プロパティ。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-273">The application specific message properties.</span></span></value>
        <remarks><span data-ttu-id="6dd2c-274">プロパティ バッグ内の各プロパティ オブジェクトのサイズは 32 キロバイトを超えることはできません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-274">The size of each property object within the Properties bag cannot exceed 32 kilobytes.</span></span>
            <span data-ttu-id="6dd2c-275">プロパティ バッグの集合的なサイズには、64 キロバイトを超えることはできません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-275">The collective size of the Properties bag cannot exceed 64 kilobytes.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-276">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-276">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="brokeredMessage.RenewLock " />
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
        <summary><span data-ttu-id="6dd2c-277">メッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-277">Renews the lock on a message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="6dd2c-278">場合<see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />が true の場合、すぐに操作を再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-278">If <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true, you can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="6dd2c-279">操作をすぐに再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-279">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="6dd2c-280">呼び出した場合にスロー<see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />遅すぎます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-280">Thrown if you have called <see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" /> too late.</span></span> <span data-ttu-id="6dd2c-281">セッションでは、このことはありませんがスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-281">In a session, this is never thrown.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="6dd2c-282">代わりにスローされる<see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" />場合は、メッセージは、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-282">Thrown instead of <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> if the message is from a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.RenewLockAsync " />
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
        <summary><span data-ttu-id="6dd2c-283">非同期的にメッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-283">Asynchronously renews the lock on a message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-284">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-284">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-285">取得またはに返信するキューのアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-285">Gets or sets the address of the queue to reply to.</span></span></summary>
        <value><span data-ttu-id="6dd2c-286">メッセージ キューのアドレスに返信します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-286">The reply to queue address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-287">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-287">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-288">取得または設定に返信するセッション識別子。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-288">Gets or sets the session identifier to reply to.</span></span></summary>
        <value><span data-ttu-id="6dd2c-289">返信するセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-289">The session identifier to reply to.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-290">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-290">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-291">取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-291">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span> <span data-ttu-id="6dd2c-292">このプロパティは、UTC 時刻を返しますプロパティを設定するときに指定された DateTime 値もあります (utc)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-292">This property returns the time in UTC; when setting the property, the supplied DateTime value must also be in UTC.</span></span></summary>
        <value><span data-ttu-id="6dd2c-293">スケジュールされたエンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-293">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="6dd2c-294">この値では、遅延メッセージを送信するためです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-294">This value is for delayed message sending.</span></span> <span data-ttu-id="6dd2c-295">後で、特定の時刻に送信するメッセージを遅延することを利用します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-295">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks> <span data-ttu-id="6dd2c-296">メッセージ enquing 時間では、メッセージを同時に送信されることは限りません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-296">Message enquing time does not mean that the message will be sent at the same time.</span></span> <span data-ttu-id="6dd2c-297">にキュー入れられたが取得されますが、実際の送信時間は、キューの作業負荷とその状態によって異なります。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-297">It will get enqueued, but the actual sending time depends on the queue's workload and its state.</span></span> <seealso cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" /></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-298">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-298">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="6dd2c-299">渡された値が DateTime.MaxValue である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-299">Thrown if the passed in value is DateTime.MaxValue.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-300">Service Bus によってメッセージに割り当てられた一意の番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-300">Gets the unique number assigned to a message by the Service Bus.</span></span></summary>
        <value><span data-ttu-id="6dd2c-301">Service Bus によってメッセージに割り当てられた一意の番号。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-301">The unique number assigned to a message by the Service Bus.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-302">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-302">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6dd2c-303">メッセージ サーバーからメッセージを受信したいない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-303">Thrown if the message was not received from the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-304">取得またはセッションの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-304">Gets or sets the identifier of the session.</span></span></summary>
        <value><span data-ttu-id="6dd2c-305">セッションの識別子。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-305">The identifier of the session.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-306">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-306">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-307">メッセージのサイズをバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-307">Gets the size of the message in bytes.</span></span></summary>
        <value><span data-ttu-id="6dd2c-308">メッセージのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-308">The message size in bytes.</span></span></value>
        <remarks><span data-ttu-id="6dd2c-309">サイズの値を正確なは、BrokeredMessage のインスタンスの送受信後のみです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-309">The value of Size is only accurate after the BrokeredMessage instance is sent or received.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-310">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-310">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessageState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As MessageState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ServiceBus.Messaging.MessageState" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-311">取得またはメッセージの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-311">Gets or sets the state of the message.</span></span></summary>
        <value><span data-ttu-id="6dd2c-312">メッセージの状態。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-312">The state of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.GetSchema">
      <MemberSignature Language="C#" Value="System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema System.Xml.Serialization.IXmlSerializable.GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#GetSchema" />
      <MemberSignature Language="VB.NET" Value="Function GetSchema () As XmlSchema Implements IXmlSerializable.GetSchema" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6dd2c-313">このメソッドは予約されているため、使用できません。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-313">This method is reserved and should not be used.</span></span> <span data-ttu-id="6dd2c-314">IXmlSerializable インターフェイスを実装する場合は、null (Visual Basic では Nothing) このメソッドから返す、代わりに、カスタム スキーマを指定することが必要な場合、この、XmlSchemaProviderAttribute をクラスに適用します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-314">When implementing the IXmlSerializable interface, you should return null (Nothing in Visual Basic) from this method, and instead, if specifying a custom schema is required, apply the XmlSchemaProviderAttribute to the class.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-315">WriteXml メソッドで作成され、ReadXml メソッドで使用されるオブジェクトの XML 表現を記述する XmlSchema です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-315">An XmlSchema that describes the XML representation of the object that is produced by the WriteXml method and consumed by the ReadXml method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.ReadXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Sub ReadXml (reader As XmlReader) Implements IXmlSerializable.ReadXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="6dd2c-316">オブジェクトの逆シリアル化元の XmlReader ストリーム。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-316">The XmlReader stream from which the object is deserialized.</span></span></param>
        <summary><span data-ttu-id="6dd2c-317">オブジェクトの XML 表現からオブジェクトを生成します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-317">Generates an object from its XML representation.</span></span> <span data-ttu-id="6dd2c-318">このメソッドは、内部使用に予約されているを指定しないで直接的または間接的に (たとえば、シリアライザーまたは、フォーマッタを使用して)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-318">This method is reserved for internal use and should not be used directly or indirectly (for example, using a serializer or a formatter).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.WriteXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Sub WriteXml (writer As XmlWriter) Implements IXmlSerializable.WriteXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="6dd2c-319">オブジェクトがシリアル化の XmlWriter ストリーム。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-319">The XmlWriter stream to which the object is serialized.</span></span></param>
        <summary><span data-ttu-id="6dd2c-320">オブジェクトを XML 表現に変換します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-320">Converts an object into its XML representation.</span></span> <span data-ttu-id="6dd2c-321">このメソッドは内部で使用するために予約済みであり直接または間接的に使用されません (シリアライザーまたは、フォーマッタを使用してなど)。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-321">This method is reserved for internal use and should not be used directly or indirectly (e.g. using a serializer or a formatter).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-322">取得または有効期限値、メッセージの時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-322">Gets or sets the message’s time to live value.</span></span> <span data-ttu-id="6dd2c-323">これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-323">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="6dd2c-324">その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-324">Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="6dd2c-325">サブスクライバーは期限切れのメッセージを受信することができません。TimeToLive はメッセージを受信できる、最大有効期間が、その値が指定されているエンティティを超えることはできません、<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />送信先のキューまたはサブスクリプション上の値。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-325">Subscribers will be unable to receive expired messages.TimeToLive is the maximum lifetime that a message can receive, but its value cannot exceed the entity specified the <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" /> value on the destination queue or subscription.</span></span> <span data-ttu-id="6dd2c-326">TimeToLive 値が低い方が指定されている場合は、個々 のメッセージに適用されます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-326">If a lower TimeToLive value is specified, it will be applied to the individual message.</span></span> <span data-ttu-id="6dd2c-327">ただし、メッセージで指定されたより大きい値は、エンティティの DefaultMessageTimeToLive 値によってオーバーライドされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-327">However, a larger value specified on the message will be overridden by the entity’s DefaultMessageTimeToLive value.</span></span></summary>
        <value><span data-ttu-id="6dd2c-328">有効期限値、メッセージの時刻。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-328">The message’s time to live value.</span></span></value>
        <remarks><span data-ttu-id="6dd2c-329">送信者がメッセージに設定された TTL を超えた場合、変換先の TTL、メッセージの TTL は、遅い方によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-329">If the TTL set on a message by the sender exceeds the destination's TTL, then the message's TTL will be overwritten by the later one.</span></span>
            <span data-ttu-id="6dd2c-330">参照してください<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />、<see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />メッセージ エンティティ レベルで TTL を制御する方法の詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-330">See <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />, <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" /> to learn more about how to control message TTL at an entity level.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-331">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-331">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="6dd2c-332">渡された値が TimeSpan.Zero に等しいまたはそれよりも小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-332">Thrown if the passed in value is less than or equal to TimeSpan.Zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-333">取得または送信をアドレスに設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-333">Gets or sets the send to address.</span></span></summary>
        <value><span data-ttu-id="6dd2c-334">アドレスに送信します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-334">The send to address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="6dd2c-335">メッセージが破棄された状態である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-335">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="brokeredMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6dd2c-336">現在のメッセージを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-336">Returns a string that represents the current message.</span></span></summary>
        <returns><span data-ttu-id="6dd2c-337">現在のメッセージの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-337">The string representation of the current message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6dd2c-338">取得またはトランザクションがある場合、転送キュー経由のメッセージを送信するために、パーティション キー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-338">Gets or sets a partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></summary>
        <value><span data-ttu-id="6dd2c-339">パーティション キーは、トランザクションがある場合、転送キュー経由のメッセージを送信するために使用する値。</span><span class="sxs-lookup"><span data-stu-id="6dd2c-339">The partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>