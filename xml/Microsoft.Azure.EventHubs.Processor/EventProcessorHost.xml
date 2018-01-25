<Type Name="EventProcessorHost" FullName="Microsoft.Azure.EventHubs.Processor.EventProcessorHost">
  <TypeSignature Language="C#" Value="public sealed class EventProcessorHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventProcessorHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventProcessorHost" />
  <TypeSignature Language="F#" Value="type EventProcessorHost = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4289e-101">Event Hubs のイベント データを処理するためには、ホストを表します。</span><span class="sxs-lookup"><span data-stu-id="4289e-101">Represents a host for processing Event Hubs event data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="4289e-102">EventHub の名前。</span><span class="sxs-lookup"><span data-stu-id="4289e-102">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="4289e-103">Event Hub 内のコンシューマー グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4289e-103">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="4289e-104">Event Hub から受信するための接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4289e-104">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="4289e-105">リースとチェックポイント処理に使用する Azure ストレージ アカウントへの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4289e-105">Connection string to Azure Storage account used for leases and checkpointing.</span></span></param>
        <param name="leaseContainerName"><span data-ttu-id="4289e-106">組み込みのリースとチェックポイント マネージャーで使用するための azure Storage コンテナー名。</span><span class="sxs-lookup"><span data-stu-id="4289e-106">Azure Storage container name for use by built-in lease and checkpoint manager.</span></span></param>
        <summary>
             <span data-ttu-id="4289e-107">Event Hub からイベントを処理する新しいホストを作成します。</span><span class="sxs-lookup"><span data-stu-id="4289e-107">Create a new host to process events from an Event Hub.</span></span>
             
             <span data-ttu-id="4289e-108"><para>Event Hubs は、スケール アウト、高トラフィックのシナリオで頻繁に使用される、ため、通常、プロセスあたり 1 つだけホストおよびする別のコンピューター上のプロセスで実行されます。ただし、通常は 1 台のコンピューター、または 1 つのプロセス内でも、複数のホストを実行するスループット問題がない場合。</para></span><span class="sxs-lookup"><span data-stu-id="4289e-108"><para>Since Event Hubs are frequently used for scale-out, high-traffic scenarios, generally there will be only one host per process, and the processes will be run on separate machines. However, it is supported to run multiple hosts on one machine, or even within one process, if throughput is not a concern.</para></span></span>
             
             <span data-ttu-id="4289e-109">このコンス トラクターのオーバー ロードでは、既定、組み込みのリースとチェックポイント マネージャーを使用します。</span><span class="sxs-lookup"><span data-stu-id="4289e-109">This overload of the constructor uses the default, built-in lease and checkpoint managers.</span></span> <span data-ttu-id="4289e-110">StorageConnectionString パラメーターで指定された Azure ストレージ アカウントは、レコードのリースとチェックポイントに組み込みの管理者によって使用されます。</span><span class="sxs-lookup"><span data-stu-id="4289e-110">The Azure Storage account specified by the storageConnectionString parameter is used by the built-in managers to record leases and checkpoints.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, class Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, class Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.EventHubs.Processor.ICheckpointManager,Microsoft.Azure.EventHubs.Processor.ILeaseManager)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, checkpointManager As ICheckpointManager, leaseManager As ILeaseManager)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * Microsoft.Azure.EventHubs.Processor.ICheckpointManager * Microsoft.Azure.EventHubs.Processor.ILeaseManager -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, checkpointManager, leaseManager)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="checkpointManager" Type="Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
        <Parameter Name="leaseManager" Type="Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="4289e-111">プロセッサのホストの名前です。</span><span class="sxs-lookup"><span data-stu-id="4289e-111">Name of the processor host.</span></span> <span data-ttu-id="4289e-112">一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="4289e-112">MUST BE UNIQUE.</span></span> <span data-ttu-id="4289e-113">一意性を確保するための Guid を含むを強くお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4289e-113">Strongly recommend including a Guid to ensure uniqueness.</span></span></param>
        <param name="eventHubPath"><span data-ttu-id="4289e-114">EventHub の名前。</span><span class="sxs-lookup"><span data-stu-id="4289e-114">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="4289e-115">Event Hub 内のコンシューマー グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4289e-115">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="4289e-116">Event Hub から受信するための接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4289e-116">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="4289e-117">パーティションのチェックポイントを処理する ICheckpointManager を実装するオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="4289e-117">Object implementing ICheckpointManager which handles partition checkpointing.</span></span></param>
        <param name="leaseManager"><span data-ttu-id="4289e-118">パーティションのリースを処理する ILeaseManager を実装するオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="4289e-118">Object implementing ILeaseManager which handles leases for partitions.</span></span></param>
        <summary>
            <span data-ttu-id="4289e-119">Event Hub からイベントを処理する新しいホストを作成します。</span><span class="sxs-lookup"><span data-stu-id="4289e-119">Create a new host to process events from an Event Hub.</span></span>
            
            <span data-ttu-id="4289e-120"><para>このコンス トラクターのオーバー ロードは、最大限の柔軟性を許可します。このいずれかにより、呼び出し元もプロセッサ ホストの名前を指定することができます。オーバー ロードでは、呼び出し元組み込み済みの Azure Storage に基づくを置換する独自のリースとチェックポイントの管理を提供することもできます。</para></span><span class="sxs-lookup"><span data-stu-id="4289e-120"><para>This overload of the constructor allows maximum flexibility. This one allows the caller to specify the name of the processor host as well. The overload also allows the caller to provide their own lease and checkpoint managers to replace the built-in ones based on Azure Storage.</para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String, Optional storageBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName, storageBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="storageBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="4289e-121">このイベント プロセッサ ホストの名前。</span><span class="sxs-lookup"><span data-stu-id="4289e-121">A name for this event processor host.</span></span> <span data-ttu-id="4289e-122">メソッドのノートを参照してください。</span><span class="sxs-lookup"><span data-stu-id="4289e-122">See method notes.</span></span></param>
        <param name="eventHubPath"><span data-ttu-id="4289e-123">EventHub の名前。</span><span class="sxs-lookup"><span data-stu-id="4289e-123">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="4289e-124">Event Hub 内のコンシューマー グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4289e-124">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="4289e-125">Event Hub から受信するための接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4289e-125">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="4289e-126">リースとチェックポイント処理に使用する Azure ストレージ アカウントへの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4289e-126">Connection string to Azure Storage account used for leases and checkpointing.</span></span></param>
        <param name="leaseContainerName"><span data-ttu-id="4289e-127">組み込みのリースとチェックポイント マネージャーで使用するための azure Storage コンテナー名。</span><span class="sxs-lookup"><span data-stu-id="4289e-127">Azure Storage container name for use by built-in lease and checkpoint manager.</span></span></param>
        <param name="storageBlobPrefix"><span data-ttu-id="4289e-128">ストレージ コンテナー内の blob の名前を付けるときに使用されるプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="4289e-128">Prefix used when naming blobs within the storage container.</span></span></param>
        <summary>
            <span data-ttu-id="4289e-129">Event Hub からイベントを処理する新しいホストを作成します。</span><span class="sxs-lookup"><span data-stu-id="4289e-129">Create a new host to process events from an Event Hub.</span></span>
            
            <span data-ttu-id="4289e-130"><para>このコンス トラクターのオーバー ロードでは、既定、組み込みのリースとチェックポイント マネージャーを使用します。</para></span><span class="sxs-lookup"><span data-stu-id="4289e-130"><para>This overload of the constructor uses the default, built-in lease and checkpoint managers.</para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4289e-131">コンシューマー グループ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="4289e-131">Gets the consumer group name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4289e-132">イベント ハブのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4289e-132">Gets the event hub path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4289e-133">プロセッサのホスト名を返します。</span><span class="sxs-lookup"><span data-stu-id="4289e-133">Returns processor host name.</span></span>
            <span data-ttu-id="4289e-134">プロセッサのホスト名が自動的に生成された場合、これは、これを取得する唯一の方法。</span><span class="sxs-lookup"><span data-stu-id="4289e-134">If the processor host name was automatically generated, this is the only way to get it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionManagerOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionManagerOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.PartitionManagerOptions : Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4289e-135">取得または設定、<see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />インスタンスによって使用される、<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4289e-135">Gets or sets the <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> instance used by the <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> object.</span></span></summary>
        <value><span data-ttu-id="4289e-136"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> インスタンス。</span><span class="sxs-lookup"><span data-stu-id="4289e-136">The <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; () where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="4289e-137">アプリケーション固有の実装<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="4289e-137">Implementation of your application specific <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></typeparam>
        <summary>
            <span data-ttu-id="4289e-138">これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />を使用してホストで実装が<see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />です。</span><span class="sxs-lookup"><span data-stu-id="4289e-138">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> implementation with the host using <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span></span>  
            <span data-ttu-id="4289e-139">これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="4289e-139">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="4289e-140">EventProcessorHost インスタンスを示すためにタスクが開始されます。</span><span class="sxs-lookup"><span data-stu-id="4289e-140">A task to indicate EventProcessorHost instance is started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; (Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;(class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1(Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) (processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync processorOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="4289e-141">アプリケーション固有の実装<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="4289e-141">Implementation of your application specific <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></typeparam>
        <param name="processorOptions">
          <span data-ttu-id="4289e-142"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />EventHub の特定のパーティションの所有権を取得したときに作成されたメッセージ ポンプのさまざまな側面を制御します。</span><span class="sxs-lookup"><span data-stu-id="4289e-142"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" /> to control various aspects of message pump created when ownership is acquired for a particular partition of EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="4289e-143">これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />を使用してホストで実装が<see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />です。</span><span class="sxs-lookup"><span data-stu-id="4289e-143">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> implementation with the host using <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span></span>  
            <span data-ttu-id="4289e-144">これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="4289e-144">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="4289e-145">EventProcessorHost インスタンスを示すためにタスクが開始されます。</span><span class="sxs-lookup"><span data-stu-id="4289e-145">A task to indicate EventProcessorHost instance is started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="4289e-146">インスタンス<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装します。</span><span class="sxs-lookup"><span data-stu-id="4289e-146">Instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation.</span></span></param>
        <summary>
            <span data-ttu-id="4289e-147">これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装のインスタンスを作成するために使用するホストと<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />所有権パーティションの場合。</span><span class="sxs-lookup"><span data-stu-id="4289e-147">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation with the host which is used to create an instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> when it takes ownership of a partition.</span></span>  <span data-ttu-id="4289e-148">これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="4289e-148">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="4289e-149">EventProcessorHost インスタンスを示すためにタスクが開始されます。</span><span class="sxs-lookup"><span data-stu-id="4289e-149">A task to indicate EventProcessorHost instance is started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory,Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory, processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory * Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync (factory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;RegisterEventProcessorFactoryAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="4289e-150">インスタンス<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装します。</span><span class="sxs-lookup"><span data-stu-id="4289e-150">Instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation.</span></span></param>
        <param name="processorOptions">
          <span data-ttu-id="4289e-151"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />EventHub の特定のパーティションの所有権を取得したときに作成されたメッセージ ポンプのさまざまな側面を制御します。</span><span class="sxs-lookup"><span data-stu-id="4289e-151"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" /> to control various aspects of message pump created when ownership is acquired for a particular partition of EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="4289e-152">これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装のインスタンスを作成するために使用するホストと<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />所有権パーティションの場合。</span><span class="sxs-lookup"><span data-stu-id="4289e-152">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation with the host which is used to create an instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> when it takes ownership of a partition.</span></span>  <span data-ttu-id="4289e-153">これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="4289e-153">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="4289e-154">EventProcessorHost インスタンスを示すためにタスクが開始されます。</span><span class="sxs-lookup"><span data-stu-id="4289e-154">A task to indicate EventProcessorHost instance is started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterEventProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterEventProcessorAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterEventProcessorAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.UnregisterEventProcessorAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterEventProcessorAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.UnregisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;UnregisterEventProcessorAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4289e-155">イベントの処理を停止します。</span><span class="sxs-lookup"><span data-stu-id="4289e-155">Stop processing events.</span></span>  <span data-ttu-id="4289e-156">シャット ダウンが完了するまでは返しません。</span><span class="sxs-lookup"><span data-stu-id="4289e-156">Does not return until the shutdown is complete.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>