<Type Name="MessagingFactorySettings" FullName="Microsoft.ServiceBus.Messaging.MessagingFactorySettings">
  <TypeSignature Language="C#" Value="public class MessagingFactorySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessagingFactorySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingFactorySettings" />
  <TypeSignature Language="F#" Value="type MessagingFactorySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e8e7f-101">メッセージングの出荷時の設定を表します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-101">Represents the messaging factory settings.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingFactorySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e8e7f-102"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingFactorySettings (Microsoft.ServiceBus.Messaging.MessagingFactorySettings other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.MessagingFactorySettings other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.#ctor(Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As MessagingFactorySettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingFactorySettings : Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="new Microsoft.ServiceBus.Messaging.MessagingFactorySettings other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="e8e7f-103">指定したメッセージング工場出荷時設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-103">The specified messaging factory settings.</span></span></param>
        <summary><span data-ttu-id="e8e7f-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />複製の工場出荷時設定の指定したメッセージングのクラスです。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> class with the specified messaging factory settings for cloning.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AmqpTransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings AmqpTransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings AmqpTransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.AmqpTransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AmqpTransportSettings As AmqpTransportSettings" />
      <MemberSignature Language="F#" Value="member this.AmqpTransportSettings : Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.AmqpTransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-105">取得またはトランスポートの設定には Advanced Message Queuing Protocol (AMQP) を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-105">Gets or set the transport settings for the Advanced Message Queuing Protocol (AMQP).</span></span></summary>
        <value><span data-ttu-id="e8e7f-106">トランスポートの設定には Advanced Message Queuing Protocol (AMQP)。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-106">The transport settings for the Advanced Message Queuing Protocol (AMQP).</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.MessagingFactorySettings Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Clone () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings&#xA;override this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactorySettings.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactorySettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e8e7f-107">コピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-107">Creates a copy of <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span></summary>
        <returns><span data-ttu-id="e8e7f-108">作成されたのコピー<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-108">A created copy of <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableEntityLevelPerformanceCounters">
      <MemberSignature Language="C#" Value="public bool DisableEntityLevelPerformanceCounters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableEntityLevelPerformanceCounters As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableEntityLevelPerformanceCounters : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.DisableEntityLevelPerformanceCounters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e7f-109">取得またはメモリ内エンティティ レベルのパフォーマンス カウンターを収集するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-109">Gets or sets a value to indicate if entity level perf counters should be collected in memory.</span></span> <span data-ttu-id="e8e7f-110">これのみに影響を与えるエンティティ レベルのカウンター、および名前空間レベルのカウンターは常に収集されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-110">Note that this only affect entity level counters, and namespace level counters are always collected.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="e8e7f-111">これは既定で false に設定 - 既定では意味場合は、このエンティティ レベルのパフォーマンス カウンター収集しないでください。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-111">By default this is set to false - meaning by default we do collect entity level perf counters.</span></span> <span data-ttu-id="e8e7f-112">この値を設定、収集された既存のカウンターは無効にし、収集される新しいエンティティからカウンターを停止するだけです。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-112">Setting this value will not affect existing collected counters, and will only stop counters from new entity being collected.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAdditionalClientTimeout">
      <MemberSignature Language="C#" Value="public bool EnableAdditionalClientTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableAdditionalClientTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.EnableAdditionalClientTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAdditionalClientTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableAdditionalClientTimeout : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.EnableAdditionalClientTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-113">取得またはその他のクライアントのタイムアウトをメッセージング操作が有効かどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-113">Gets or sets a value that indicates whether the messaging operation enables additional client timeout.</span></span></summary>
        <value><span data-ttu-id="e8e7f-114">メッセージング操作は、その他のクライアントのタイムアウトを有効にした場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-114">true if the messaging operation enables additional client timeout; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetMessagingTransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings NetMessagingTransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings NetMessagingTransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.NetMessagingTransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property NetMessagingTransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.NetMessagingTransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.NetMessagingTransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-115">取得または net メッセージングに必要なトランスポート設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-115">Gets or sets the transport settings required for the net messaging.</span></span></summary>
        <value><span data-ttu-id="e8e7f-116">Net メッセージングに必要なトランスポート設定。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-116">The transport settings required for the net messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateFactory (System.Collections.Generic.IEnumerable&lt;Uri&gt; uriAddresses, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateFactory(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; uriAddresses, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnBeginCreateFactory(System.Collections.Generic.IEnumerable{System.Uri},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateFactory (uriAddresses As IEnumerable(Of Uri), callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateFactory : seq&lt;Uri&gt; * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateFactory : seq&lt;Uri&gt; * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactorySettings.OnBeginCreateFactory (uriAddresses, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uriAddresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="uriAddresses"><span data-ttu-id="e8e7f-117">Uniform resource identifier のコレクション。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-117">The collection of uniform resource identifiers.</span></span></param>
        <param name="callback"><span data-ttu-id="e8e7f-118">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-118">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="e8e7f-119">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-119">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="e8e7f-120">非同期の実行の開始が工場出荷時のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-120">Executes the asynchronous begin create factory action.</span></span></summary>
        <returns><span data-ttu-id="e8e7f-121"><see cref="T:System.IAsyncResult" />ファクトリを作成する非同期要求を参照します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-121">An <see cref="T:System.IAsyncResult" /> that references the asynchronous request to create factory.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateFactory (Uri uri, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateFactory(class System.Uri uri, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnBeginCreateFactory(System.Uri,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateFactory : Uri * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateFactory : Uri * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactorySettings.OnBeginCreateFactory (uri, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="e8e7f-122">Uniform resource identifier です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-122">The uniform resource identifier.</span></span></param>
        <param name="callback"><span data-ttu-id="e8e7f-123">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-123">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="e8e7f-124">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-124">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="e8e7f-125">非同期の実行の開始が工場出荷時のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-125">Executes the asynchronous begin create factory action.</span></span></summary>
        <returns><span data-ttu-id="e8e7f-126"><see cref="T:System.IAsyncResult" />ファクトリを作成する非同期要求を参照します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-126">An <see cref="T:System.IAsyncResult" /> that references the asynchronous request to create factory.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessagingFactory OnEndCreateFactory (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessagingFactory OnEndCreateFactory(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnEndCreateFactory(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnEndCreateFactory (result As IAsyncResult) As MessagingFactory" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateFactory : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory&#xA;override this.OnEndCreateFactory : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="messagingFactorySettings.OnEndCreateFactory result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="e8e7f-127"><see cref="T:System.IAsyncResult" />ファクトリを作成する非同期要求を参照します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-127">An <see cref="T:System.IAsyncResult" /> that references the asynchronous request to create factory.</span></span></param>
        <summary><span data-ttu-id="e8e7f-128">ファクトリの作成への非同期要求を終了します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-128">Ends an asynchronous request to create factory.</span></span></summary>
        <returns><span data-ttu-id="e8e7f-129">新しく作成されたメッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-129">The newly created messaging factory.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-130">取得または設定、<see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-130">Gets or sets the <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="e8e7f-131"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-131">The <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out. The default value is one minute.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="e8e7f-132">Null 値が設定されています。たとえば、null 許容<see cref="T:System.TimeSpan" />です。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-132">A null is set; for example, a nullable <see cref="T:System.TimeSpan" />.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e8e7f-133">0 または負<see cref="T:System.TimeSpan" />が設定されています。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-133">A zero or negative <see cref="T:System.TimeSpan" /> is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.TokenProvider with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-134">取得または設定を出荷時のトークン プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-134">Gets or sets the token provider of the factory settings.</span></span></summary>
        <value><span data-ttu-id="e8e7f-135">工場出荷時設定のトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-135">The token provider of the factory settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.ServiceBus.Messaging.TransportType with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e8e7f-136">取得またはメッセージのトランスポートの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-136">Gets or sets the messaging transport type.</span></span></summary>
        <value><span data-ttu-id="e8e7f-137">メッセージのトランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="e8e7f-137">The messaging transport type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>