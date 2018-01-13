<Type Name="EventHubReceiver" FullName="Microsoft.ServiceBus.Messaging.EventHubReceiver">
  <TypeSignature Language="C#" Value="public sealed class EventHubReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubReceiver = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="7c2ae-101">使用されるクライアント クラスには、イベント ハブ コンシューマー グループに関連する操作が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-101">A client class used in receive operations related to an Event Hub consumer group.</span></span> <span data-ttu-id="7c2ae-102">コンシューマー グループ内の特定の Event Hub パーティションに論理受信接続を表します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-102">Represents a logical receiver connection to a specific Event Hub partition within a consumer group.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-103">受信操作中にパーティションの所有権を決定するために使用するエポック値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-103">Gets the epoch value that is used to determine partition ownership during the receive operation.</span></span></summary>
        <value><span data-ttu-id="7c2ae-104"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-104">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-105">イベント ハブのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-105">Gets the event hub path.</span></span></summary>
        <value><span data-ttu-id="7c2ae-106">イベント ハブのパス。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-106">The event hub path.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-107">受信アダプターの作成時に設定されている受信者の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-107">Gets the identifier of a receiver which was set during the creation of the receiver.</span></span></summary>
        <value><span data-ttu-id="7c2ae-108">受信者の識別子を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-108">A string representing the identifier of a receiver.</span></span> <span data-ttu-id="7c2ae-109">識別子が設定されていない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-109">It will return null if the identifier is not set.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-110">イベント ハブの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-110">Gets the name of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="7c2ae-111">イベント ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-111">The name of the Event Hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="public bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-112">示す値を取得するかどうか<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-112">Gets a value indicating whether <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="7c2ae-113">通常、最初のイベントが返されますが、イベントの開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-113">Normally, the first event returned is the event after the starting offset.</span></span></summary>
        <value><span data-ttu-id="7c2ae-114"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-114">Returns <see cref="T:System.Boolean" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubReceiver.OnAbort " />
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
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginOpen (timeout, callback, state)" />
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
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnClose timeout" />
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
        <param name="timeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndClose result" />
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
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndOpen result" />
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
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpen">
      <MemberSignature Language="C#" Value="protected override void OnOpen (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnOpen(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnOpen timeout" />
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
        <param name="timeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-115">Event Hub の論理パーティションのパーティション ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-115">Gets the partition ID for a logical partition of an Event Hub.</span></span></summary>
        <value><span data-ttu-id="7c2ae-116">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-116">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-117">取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-117">Gets or sets the number of events that any receive operation will actively cache.</span></span> <span data-ttu-id="7c2ae-118">既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-118">By default, this value is inherited from <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</span></span> <span data-ttu-id="7c2ae-119">既定値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-119">The default value is 300.</span></span></summary>
        <value><span data-ttu-id="7c2ae-120">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-120">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="7c2ae-121">この値に変更を次に、使用されますが、これには影響しません、受信側によって既にキャッシュされているイベントの数に、操作を受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-121">Changes to this value will be used in next receive operation, however this does not affect the number of events already cached by the receiver.</span></span> <span data-ttu-id="7c2ae-122">このプロパティを 0 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />を null にします。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-122">Setting this property to non-zero value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" /> to null.</span></span>
            <span data-ttu-id="7c2ae-123">注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-123">Note that setting the count too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7c2ae-124">値が 10 の必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-124">Thrown if the value is less than the minimum required value of 10.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-125">取得または設定の最大サイズ (バイト単位) のいずれかの受信操作の合計がアクティブにキャッシュされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-125">Gets or sets the maximum size (in bytes) in total that any receive operation will actively cache.</span></span> <span data-ttu-id="7c2ae-126">各イベント データのサイズによって、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-126">The size of each event data is determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> property.</span></span></summary>
        <value><span data-ttu-id="7c2ae-127"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-127">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks><span data-ttu-id="7c2ae-128">サイズの上限は、絶対的な制限ではありません。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-128">The size limit is not an absolute limit.</span></span> <span data-ttu-id="7c2ae-129">サイズにサイズの価値を少なくとも 1 つのイベント データを使って実行されます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-129">the size might go over by at least one event data worth of size.</span></span> <span data-ttu-id="7c2ae-130">この値に変更を次に、使用されますが、これには影響しません、受信側によって既にキャッシュされているイベントの数に、操作を受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-130">Changes to this value will be used in next receive operation, however this does not affect the number of events already cached by the receiver.</span></span> <span data-ttu-id="7c2ae-131">このプロパティを null 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />をゼロにします。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-131">Setting this property to non-null value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" /> to zero.</span></span>
            <span data-ttu-id="7c2ae-132">低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-132">Note that setting the size too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7c2ae-133">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-133">Thrown when the size value is less than the minimum required value of 260K bytes.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive " />
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
        <summary><span data-ttu-id="7c2ae-134">Event Hubs のイベント データを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-134">Receives Event Hubs event data.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-135">返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />オブジェクト、またはイベントのデータがない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-135">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> object, or null if no event data is available.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7c2ae-136">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-136">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7c2ae-137">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-137">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7c2ae-138">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-138">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7c2ae-139">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-139">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7c2ae-140">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-140">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <summary><span data-ttu-id="7c2ae-141">指定された数までの Event Hubs イベント データを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-141">Receives Event Hubs event data, up to the specified count.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-142">返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-142">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection.</span></span> <span data-ttu-id="7c2ae-143">コレクションが空の場合は、イベントが返されない、指定された時間、またはすべてのイベント内で最大<paramref name="maxCount" />が返されます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-143">The collection is either empty if no event is returned within the specified time, or all events up to <paramref name="maxCount" /> are returned.</span></span></returns>
        <remarks><span data-ttu-id="7c2ae-144">サービスは待たず<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-144">Service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7c2ae-145">使用可能なイベントがあると、すぐに返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-145">It returns as soon as there are any events available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7c2ae-146">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-146">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7c2ae-147">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-147">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7c2ae-148">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-148">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7c2ae-149">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-149">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (waitTime As TimeSpan) As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime"><span data-ttu-id="7c2ae-150">ユーザーがイベント データの到着を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-150">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7c2ae-151">指定されたタイムアウト値を持つ Event Hubs のイベント データを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-151">Receives Event Hubs event data with the specified timeout value.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-152">返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション、または使用可能なイベント データがない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-152">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection, or null if there is no event data available.</span></span></returns>
        <remarks>
          <span data-ttu-id="7c2ae-153"><paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-153"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7c2ae-154">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-154">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7c2ae-155">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-155">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7c2ae-156">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-156">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7c2ae-157">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-157">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer, waitTime As TimeSpan) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7c2ae-158">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-158">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <param name="waitTime"><span data-ttu-id="7c2ae-159">ユーザーがイベント データの到着を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-159">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7c2ae-160">指定されたタイムアウト値を持つ、指定された数までの Event Hubs のイベント データを受信します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-160">Receives Event Hubs event data, up to the specified count with the specified timeout value.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-161">返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-161">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection.</span></span> <span data-ttu-id="7c2ae-162">コレクションが空の場合は、イベントが返されない、指定された時間、またはすべてのイベント内で最大<paramref name="maxCount" />が返されます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-162">The collection is either empty if no event is returned within the specified time, or all events up to <paramref name="maxCount" /> are returned.</span></span></returns>
        <remarks>
          <span data-ttu-id="7c2ae-163"><paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-163"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span> <span data-ttu-id="7c2ae-164">サービスを待機しませんまた<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-164">Also service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7c2ae-165">使用可能なイベントがあると、すぐに返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-165">it returns as soon as there are any events available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7c2ae-166">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-166">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7c2ae-167">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-167">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7c2ae-168">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-168">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7c2ae-169">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-169">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7c2ae-170"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-170">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-171">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-171">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7c2ae-172">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-172">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <summary><span data-ttu-id="7c2ae-173"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-173">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-174"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-174">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="7c2ae-175">サービスは待たず<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-175">Service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7c2ae-176">使用可能なイベントがあると、すぐに返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-176">It returns as soon as there are any events available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (waitTime As TimeSpan) As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime"><span data-ttu-id="7c2ae-177">ユーザーがイベント データの到着を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-177">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7c2ae-178"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-178">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-179">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-179">The task representing the asynchronous operation.</span></span></returns>
        <remarks>
          <span data-ttu-id="7c2ae-180"><paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-180"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7c2ae-181">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-181">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <param name="waitTime"><span data-ttu-id="7c2ae-182">ユーザーがイベント データの到着を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-182">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7c2ae-183"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-183">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />.</span></span></summary>
        <returns><span data-ttu-id="7c2ae-184"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-184">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>
          <span data-ttu-id="7c2ae-185"><paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-185"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span> <span data-ttu-id="7c2ae-186">サービスを待機しませんまた<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-186">Also service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7c2ae-187">使用可能なイベントがあると、すぐに返します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-187">It returns as soon as there are any events available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="7c2ae-188">受信側のランタイム メトリックが有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-188">Gets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c2ae-189">Event Hub の論理パーティションのランタイム情報のおおよその受信者を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-189">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="7c2ae-190">設定を有効にするを参照してください<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" />と<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="7c2ae-190">To enable the setting, refer to <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" /> and <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingDateTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartingDateTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartingDateTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingDateTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartingDateTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-191">この受信者を表す UTC 形式で開始の日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-191">Gets the starting date and time in UTC format for this receiver.</span></span> <span data-ttu-id="7c2ae-192"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />メソッドは、その後、次のイベントの受信を開始<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />値。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-192">The <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> method starts receiving the next event after this <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" /> value.</span></span> <span data-ttu-id="7c2ae-193">Null の場合、受信側は、Event Hubs のイベント ストリームの先頭からのイベントの受信を開始します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-193">If null, the receiver starts receiving events from the beginning of the Event Hubs event stream.</span></span></summary>
        <value><span data-ttu-id="7c2ae-194">開始の日付と時刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-194">The starting date and time in UTC.</span></span></value>
        <remarks><span data-ttu-id="7c2ae-195">サービスは、次のイベントを配信するときだけこの datetime と概算値として使用します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-195">Service only uses this datetime as an approximation when delivering next event.</span></span>
            <span data-ttu-id="7c2ae-196">留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-196">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingOffset">
      <MemberSignature Language="C#" Value="public string StartingOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartingOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartingOffset : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7c2ae-197">この受信者の開始オフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-197">Gets the starting offset for this receiver.</span></span> <span data-ttu-id="7c2ae-198"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />メソッドは、このオフセット値後は、次のイベントの受信を開始します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-198">The <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> method starts receiving the next event after this offset value.</span></span> <span data-ttu-id="7c2ae-199">値が null の場合、受信側は、Event Hubs のイベント ストリームの先頭からのイベントの受信を開始します。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-199">If the value is null, the receiver starts receiving events from the beginning of the Event Hubs event stream.</span></span></summary>
        <value><span data-ttu-id="7c2ae-200">開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-200">The starting offset.</span></span></value>
        <remarks><span data-ttu-id="7c2ae-201">によって表される 1 つのパーティションのみに結び付ける開始オフセットこの<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="7c2ae-201">This starting offset ties to one partition only, represented by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>