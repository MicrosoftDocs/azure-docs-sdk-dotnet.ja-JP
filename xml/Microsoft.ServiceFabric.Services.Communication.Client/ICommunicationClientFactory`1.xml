<Type Name="ICommunicationClientFactory&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public interface ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationClientFactory`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="b9890-101">クライアントの通信の種類</span><span class="sxs-lookup"><span data-stu-id="b9890-101">Type of communication client</span></span></typeparam>
    <summary>
            <span data-ttu-id="b9890-102">Service fabric サービスと対話する通信のクライアントのファクトリを提供するために実装する必要があります、インターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="b9890-102">Defines the interface that must be implemented to provide a factory for communication clients to talk to a service fabric service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9890-103">通信のクライアントがサービス エンドポイントに接続するときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b9890-103">Event handler that is fired when the Communication client connects to the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9890-104">通信のクライアントがサービス エンドポイントから切断するときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b9890-104">Event handler that is fired when the Communication client disconnects from the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (previousRsp, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="b9890-105">以前の ResolvedServicePartition 値</span><span class="sxs-lookup"><span data-stu-id="b9890-105">Previous ResolvedServicePartition value</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b9890-106">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b9890-106">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b9890-107">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b9890-107">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b9890-108">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b9890-108">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b9890-109">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b9890-109">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b9890-110">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを再解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b9890-110">Re-resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="b9890-111">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b9890-111">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b9890-112">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b9890-112">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b9890-113">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b9890-113">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="b9890-114">サービスの Uri を解決するのには</span><span class="sxs-lookup"><span data-stu-id="b9890-114">Uri of the service to resolve</span></span></param>
        <param name="partitionKey"><span data-ttu-id="b9890-115">解決するのには、パーティションを識別するキー</span><span class="sxs-lookup"><span data-stu-id="b9890-115">Key that identifies the partition to resolve</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b9890-116">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b9890-116">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b9890-117">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b9890-117">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b9890-118">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b9890-118">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b9890-119">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b9890-119">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b9890-120">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b9890-120">Resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="b9890-121">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b9890-121">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b9890-122">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b9890-122">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b9890-123">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b9890-123">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync (TCommunicationClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync(!TCommunicationClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="iCommunicationClientFactory.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="b9890-124">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="b9890-124">Communication client</span></span></param>
        <param name="exceptionInformation"><span data-ttu-id="b9890-125">サービスと通信中に発生した例外に関する情報。</span><span class="sxs-lookup"><span data-stu-id="b9890-125">Information about exception that happened while communicating with the service.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b9890-126">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b9890-126">Specifies the retry policy that should be used for handling the reported exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b9890-127">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b9890-127">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b9890-128">サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。</span><span class="sxs-lookup"><span data-stu-id="b9890-128">Handles the exceptions that occur in the CommunicationClient when sending a message to the Service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b9890-129">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b9890-129">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b9890-130">タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />再試行ポリシーでこの例外の情報を提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b9890-130">The result of the Task is a <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> object that provides information on retry policy for this exception.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>