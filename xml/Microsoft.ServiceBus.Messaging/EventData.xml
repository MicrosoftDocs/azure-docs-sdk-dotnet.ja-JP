<Type Name="EventData" FullName="Microsoft.ServiceBus.Messaging.EventData">
  <TypeSignature Language="C#" Value="public sealed class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventData" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
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
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="efccf-101">Event Hubs ストリームから送受信されたイベントを表します。</span><span class="sxs-lookup"><span data-stu-id="efccf-101">Represents the event sent and received from an Event Hubs stream.</span></span> <span data-ttu-id="efccf-102">イベント、ユーザー定義のプロパティ バッグ、およびパーティション内のオフセットやストリーム シーケンスでは、その番号など、イベントを説明するさまざまなメタデータの本文が含まれています。</span><span class="sxs-lookup"><span data-stu-id="efccf-102">It contains the body of the event, a user-defined property bag, and various metadata describing the event, such as its offset in the partition and its number in the stream sequence.</span></span> <span data-ttu-id="efccf-103">パーティションには、一連のイベント データが格納されます。</span><span class="sxs-lookup"><span data-stu-id="efccf-103">Partitions are filled with a sequence of event data.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="efccf-104"><see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="efccf-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : byte[] -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray"><span data-ttu-id="efccf-105">本文ストリームを形成するために使用、イベントのデータ バイトの配列。</span><span class="sxs-lookup"><span data-stu-id="efccf-105">The event data byte array which is used to form the body stream.</span></span></param>
        <summary><span data-ttu-id="efccf-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />を本文として指定したバイト配列を使用するクラス。</span><span class="sxs-lookup"><span data-stu-id="efccf-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the specified byte array as the body.</span></span></summary>
        <remarks><span data-ttu-id="efccf-107">EventData を送信するときに、入力バイト配列を変更不可として扱う必要があります。</span><span class="sxs-lookup"><span data-stu-id="efccf-107">You should treat the input byte array as immutable when sending EventData.</span></span> 
            
            <span data-ttu-id="efccf-108">データだけでなく、複製操作を送信するときに Service Bus はバイト配列参照によってではなくをしてアクセス バイト配列のディープ コピーです。</span><span class="sxs-lookup"><span data-stu-id="efccf-108">When sending the data as well as any cloning operation, Service Bus will access the byte array by reference rather that by deep copy of the byte array.</span></span> <span data-ttu-id="efccf-109">EventData インスタンスを破棄しても、配列との関連付けが逆参照がのみです。</span><span class="sxs-lookup"><span data-stu-id="efccf-109">Also disposing the EventData instance will only de-reference the association with the array.</span></span> <span data-ttu-id="efccf-110">ユーザーは、バイト配列自体のライフ サイクルを担当します。</span><span class="sxs-lookup"><span data-stu-id="efccf-110">The user is responsible for the lifecycle of the byte-array itself.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; arraySegments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; arraySegments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Collections.Generic.IList{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegments As IList(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData arraySegments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegments" Type="System.Collections.Generic.IList&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegments"><span data-ttu-id="efccf-111">本文として送信するには、配列セグメントの IList、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />です。</span><span class="sxs-lookup"><span data-stu-id="efccf-111">An IList of array segments to be sent as the body of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</span></span>
            </param>
        <summary><span data-ttu-id="efccf-112">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />を本文として指定したバイト配列セグメントの一覧を使用するクラス。</span><span class="sxs-lookup"><span data-stu-id="efccf-112">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the specified list of byte array segments as the body.</span></span></summary>
        <remarks><span data-ttu-id="efccf-113">ユーザーが IList を使用して通常&lt;ArraySegment&lt;バイト&gt;&gt;を使用する場合がバッファー プール メモリの効率的な使用を必要とするシナリオを自分が所有します。</span><span class="sxs-lookup"><span data-stu-id="efccf-113">Typically user will use IList&lt;ArraySegment&lt;byte&gt;&gt; when using there own buffer pool for scenarios that require efficient usage of memory.</span></span>
            
            <span data-ttu-id="efccf-114">データだけでなく、複製操作を送信するときに Service Bus にアクセスする配列セグメント参照によってではなくをバイトのディープ コピーです。</span><span class="sxs-lookup"><span data-stu-id="efccf-114">When sending the data as well as any cloning operation, Service Bus will access the array segments by reference rather that by deep copy of the bytes.</span></span> 
            
            <span data-ttu-id="efccf-115">EventData インスタンスを破棄しても、リストとの関連付けが解除参照はのみです。</span><span class="sxs-lookup"><span data-stu-id="efccf-115">Disposing the EventData instance will only de-reference the association with the list.</span></span> <span data-ttu-id="efccf-116">ユーザーは、自分自身配列セグメントのライフ サイクルを担当します。</span><span class="sxs-lookup"><span data-stu-id="efccf-116">User is responsible for the life cycle of the array segments themselves.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="efccf-117">本文ストリームとして使用されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="efccf-117">A stream which is used as the body stream.</span></span></param>
        <summary><span data-ttu-id="efccf-118">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />本文ストリームとして引数のストリームを使用するクラス。</span><span class="sxs-lookup"><span data-stu-id="efccf-118">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the argument stream as the body stream.</span></span></summary>
        <remarks><span data-ttu-id="efccf-119">ユーザーは、このコンス トラクターを使用する場合に、ストリームの破棄を所有すると想定されます。</span><span class="sxs-lookup"><span data-stu-id="efccf-119">User is expected to own the disposing of the stream when using this constructor.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (object content, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object content, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData (content, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="efccf-120">.Net オブジェクト</span><span class="sxs-lookup"><span data-stu-id="efccf-120">.Net object</span></span></param>
        <param name="serializer"><span data-ttu-id="efccf-121">シリアル化に使用されるシリアライザー<paramref name="content" /></span><span class="sxs-lookup"><span data-stu-id="efccf-121">the serializer used to serialize <paramref name="content" /></span></span></param>
        <summary>
            <span data-ttu-id="efccf-122">入力のコンテンツと本文ストリームを作成するシリアライザーを受け取るコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="efccf-122">Constructor which takes the input content and serializer to create the body stream.</span></span>
            </summary>
        <remarks><span data-ttu-id="efccf-123">コンテンツがある場合、ストリームと seriazlier が null で使用する時と見なされることが<see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></span><span class="sxs-lookup"><span data-stu-id="efccf-123">If content is a stream and seriazlier is null, then it is equate to use <see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventData" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventData.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="efccf-124">このイベント データのディープ コピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="efccf-124">Makes a deep copy of this event data.</span></span></summary>
        <returns><span data-ttu-id="efccf-125">このイベント データのコピー。</span><span class="sxs-lookup"><span data-stu-id="efccf-125">A copy of this event data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
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
        <summary><span data-ttu-id="efccf-126">アンマネージ リソースの解放またはリセットに関連付けられているアプリケーション定義のタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="efccf-126">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-127">取得または送信時刻の日時を UTC に設定します。</span><span class="sxs-lookup"><span data-stu-id="efccf-127">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="efccf-128">エンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="efccf-128">The enqueue time in UTC.</span></span> <span data-ttu-id="efccf-129">この値は、エンキュー イベント データの実際の時間を表します。</span><span class="sxs-lookup"><span data-stu-id="efccf-129">This value represents the actual time of enqueuing the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="eventData.GetBodyStream " />
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
        <summary><span data-ttu-id="efccf-130">取得またはイベント データの本体を基になるストリームを設定します。</span><span class="sxs-lookup"><span data-stu-id="efccf-130">Gets or sets the underlying stream to the event data body.</span></span></summary>
        <returns><span data-ttu-id="efccf-131">イベント データの本体を基になるストリーム。</span><span class="sxs-lookup"><span data-stu-id="efccf-131">The underlying stream to the event data body.</span></span></returns>
        <remarks><span data-ttu-id="efccf-132">このメソッドは、1 回のみ呼び出すことができ、メソッドはスロー後<see cref="T:System.InvalidOperationException" />です。</span><span class="sxs-lookup"><span data-stu-id="efccf-132">This method can only be called once and afterwards method will throw <see cref="T:System.InvalidOperationException" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="eventData.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="efccf-133">イベント データのバイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="efccf-133">Gets the event data bytes.</span></span></summary>
        <returns><span data-ttu-id="efccf-134">イベントのデータ バイトです。</span><span class="sxs-lookup"><span data-stu-id="efccf-134">The event data bytes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-135">イベント ハブ パーティション ストリームに対して相対的には、データのオフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="efccf-135">Gets the offset of the data relative to the Event Hub partition stream.</span></span> <span data-ttu-id="efccf-136">オフセットは、マーカーまたは Event Hubs ストリーム内のイベントの識別子です。</span><span class="sxs-lookup"><span data-stu-id="efccf-136">The offset is a marker or identifier for an event within the Event Hubs stream.</span></span> <span data-ttu-id="efccf-137">識別子は、Event Hubs ストリームのパーティション内で一意です。</span><span class="sxs-lookup"><span data-stu-id="efccf-137">The identifier is unique within a partition of the Event Hubs stream.</span></span></summary>
        <value><span data-ttu-id="efccf-138">イベント データの読み取りのオフセット。</span><span class="sxs-lookup"><span data-stu-id="efccf-138">The read offset of the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-139">取得またはイベント データを送信するパーティションを決定するために使用するキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="efccf-139">Gets or sets the key that is used to determine to which partition to send event data.</span></span></summary>
        <value><span data-ttu-id="efccf-140">イベント データを送信するパーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="efccf-140">A partition key for the partition to which event data should be sent.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-141">ユーザーのプロパティの中に明示的に追加されたユーザーが操作を送信するイベント データを取得します。</span><span class="sxs-lookup"><span data-stu-id="efccf-141">Gets the user properties of the event data that the user explicitly added during send operations.</span></span></summary>
        <value><span data-ttu-id="efccf-142">イベント データのユーザーのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="efccf-142">The user properties of the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-143">Event Hub のパーティションのストリーム内のイベントの論理シーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="efccf-143">Gets the logical sequence number of the event within the partition stream of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="efccf-144">イベントの論理シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="efccf-144">The logical sequence number of the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializedSizeInBytes">
      <MemberSignature Language="C#" Value="public long SerializedSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SerializedSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializedSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SerializedSizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="efccf-145">取得またはイベント データを含む、システムのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="efccf-145">Gets or sets the system properties, including the event data.</span></span></summary>
        <value><span data-ttu-id="efccf-146">イベント データを含むシステム プロパティ。</span><span class="sxs-lookup"><span data-stu-id="efccf-146">The system properties, including the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>