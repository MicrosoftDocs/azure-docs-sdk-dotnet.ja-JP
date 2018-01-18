<Type Name="CommunicationClientFactoryBase&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public abstract class CommunicationClientFactoryBase&lt;TCommunicationClient&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CommunicationClientFactoryBase`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CommunicationClientFactoryBase(Of TCommunicationClient)&#xA;Implements ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    interface ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt;" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="43a64-101">クライアントの通信の種類</span><span class="sxs-lookup"><span data-stu-id="43a64-101">The type of communication client</span></span></typeparam>
    <summary>
            <span data-ttu-id="43a64-102">Service fabric サービスと対話する通信のクライアントを作成するためには、ICommunicationClientFactory の基本実装を提供します。</span><span class="sxs-lookup"><span data-stu-id="43a64-102">Provides the base implementation of ICommunicationClientFactory for creating communication clients to talk to service fabric services.</span></span> <span data-ttu-id="43a64-103">カスタム トランスポートの実装のための通信のクライアントを作成する CommunicationClientFactoryBase クラスを拡張します。</span><span class="sxs-lookup"><span data-stu-id="43a64-103">Extend the CommunicationClientFactoryBase class to create communication clients for custom transport implementations.</span></span> <span data-ttu-id="43a64-104">このクラスは、通信のクライアントのキャッシュを保持し、同じサービス エンドポイントへの要求のクライアントを再利用しようとしています。</span><span class="sxs-lookup"><span data-stu-id="43a64-104">This class maintains a cache of communication clients and attempts to reuse the clients for requests to the same service endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CommunicationClientFactoryBase (Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.#ctor(Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (Optional servicePartitionResolver As IServicePartitionResolver = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional traceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; (servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePartitionResolver"><span data-ttu-id="43a64-105">省略可能な ServicePartitionResolver</span><span class="sxs-lookup"><span data-stu-id="43a64-105">Optional ServicePartitionResolver</span></span></param>
        <param name="exceptionHandlers"><span data-ttu-id="43a64-106">サービスの通信チャネルにクライアントでの例外の省略可能なカスタム例外ハンドラー</span><span class="sxs-lookup"><span data-stu-id="43a64-106">Optional Custom exception handlers for the exceptions on the Client to Service communication channel</span></span></param>
        <param name="traceId"><span data-ttu-id="43a64-107">このコンポーネントから診断トレースに使用する識別子</span><span class="sxs-lookup"><span data-stu-id="43a64-107">Identifier to use in diagnostics traces from this component</span></span> </param>
        <summary>
            <span data-ttu-id="43a64-108">通信のクライアントのファクトリの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="43a64-108">Initializes a new instance of the communication client factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortClient">
      <MemberSignature Language="C#" Value="protected abstract void AbortClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AbortClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.AbortClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AbortClient (client As TCommunicationClient)" />
      <MemberSignature Language="F#" Value="abstract member AbortClient : 'CommunicationClient -&gt; unit" Usage="communicationClientFactoryBase.AbortClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="43a64-109">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="43a64-109">Communication client</span></span></param>
        <summary>
            <span data-ttu-id="43a64-110">指定したクライアントを中止します。</span><span class="sxs-lookup"><span data-stu-id="43a64-110">Aborts the given client</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43a64-111">通信のクライアントがサービス エンドポイントに接続するときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="43a64-111">Event handler that is fired when the Communication client connects to the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43a64-112">通信のクライアントがサービス エンドポイントから切断するときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="43a64-112">Event handler that is fired when the Communication client disconnects from the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;TCommunicationClient&gt; CreateClientAsync (string endpoint, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; CreateClientAsync(string endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.CreateClientAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateClientAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.CreateClientAsync (endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="43a64-113">レプリカがリッスンしているリスナーのアドレス</span><span class="sxs-lookup"><span data-stu-id="43a64-113">listener address where the replica is listening</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43a64-114">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43a64-114">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="43a64-115">指定したエンドポイント アドレスの通信のクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="43a64-115">Creates a communication client for the given endpoint address.</span></span>
            </summary>
        <returns><span data-ttu-id="43a64-116">作成された通信のクライアント</span><span class="sxs-lookup"><span data-stu-id="43a64-116">The communication client that was created</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionHandlers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ExceptionHandlers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionHandlers As IEnumerable(Of IExceptionHandler)" />
      <MemberSignature Language="F#" Value="member this.ExceptionHandlers : seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ExceptionHandlers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43a64-117">サービスの通信チャネルをクライアント上で例外を処理するためには、カスタム例外ハンドラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="43a64-117">Gets the custom exception handlers for handling exceptions on the client to service communication channel.</span></span>
            </summary>
        <value><span data-ttu-id="43a64-118">例外ハンドラーの一覧</span><span class="sxs-lookup"><span data-stu-id="43a64-118">List of Exception handlers</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (previousRsp, targetReplica, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplica" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="43a64-119">以前の ResolvedServicePartition 値</span><span class="sxs-lookup"><span data-stu-id="43a64-119">Previous ResolvedServicePartition value</span></span></param>
        <param name="targetReplica"><span data-ttu-id="43a64-120">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="43a64-120">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="43a64-121">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="43a64-121">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="43a64-122">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="43a64-122">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43a64-123">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43a64-123">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="43a64-124">取得または指定された previousRsp に基づいて解決することによって、指定したリスナー名の CommunicationClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="43a64-124">Gets or Creates the CommunicationClient for the specified listener name by resolving based on the given previousRsp.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="43a64-125">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="43a64-125">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="43a64-126">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43a64-126">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="serviceUri"><span data-ttu-id="43a64-127">サービスの Uri を解決するのには</span><span class="sxs-lookup"><span data-stu-id="43a64-127">Uri of the service to resolve</span></span></param>
        <param name="partitionKey"><span data-ttu-id="43a64-128">解決するのには、パーティションを識別するキー</span><span class="sxs-lookup"><span data-stu-id="43a64-128">Key that identifies the partition to resolve</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="43a64-129">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="43a64-129">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="43a64-130">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="43a64-130">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="43a64-131">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="43a64-131">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43a64-132">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43a64-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="43a64-133">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="43a64-133">Resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="43a64-134">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="43a64-134">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="43a64-135">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="43a64-135">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="43a64-136">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43a64-136">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync (TCommunicationClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync(!TCommunicationClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;&#xA;override this.ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="communicationClientFactoryBase.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;ReportOperationExceptionAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="client"><span data-ttu-id="43a64-137">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="43a64-137">Communication client</span></span></param>
        <param name="exceptionInformation"><span data-ttu-id="43a64-138">サービスと通信するときに発生した例外に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="43a64-138">Information about the exception that occurred when communicating with the service.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="43a64-139">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="43a64-139">Specifies the retry policy that should be used for handling the reported exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43a64-140">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43a64-140">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="43a64-141">サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。</span><span class="sxs-lookup"><span data-stu-id="43a64-141">Handles the exceptions that occur in the CommunicationClient when sending a message to the Service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="43a64-142">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="43a64-142">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="43a64-143">タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />オブジェクトを決定する方法この例外の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="43a64-143">The result of the Task is a <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> object that determines how the retry policy for this exception.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceResolver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ServiceResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceResolver As IServicePartitionResolver" />
      <MemberSignature Language="F#" Value="member this.ServiceResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43a64-144">サービス エンドポイントを解決するために、クライアント ファクトリによって使用される ServicePartitionResolver を取得します。</span><span class="sxs-lookup"><span data-stu-id="43a64-144">Gets the ServicePartitionResolver used by the client factory for resolving the service endpoint.</span></span>
            </summary>
        <value><span data-ttu-id="43a64-145">ServicePartitionResolver</span><span class="sxs-lookup"><span data-stu-id="43a64-145">ServicePartitionResolver</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="protected string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.TraceId" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TraceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43a64-146">このコンポーネントの診断トレース識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="43a64-146">Gets the diagnostics trace identifier for this component.</span></span>
            </summary>
        <value><span data-ttu-id="43a64-147">トレース識別子</span><span class="sxs-lookup"><span data-stu-id="43a64-147">Trace identifier</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="43a64-148">通信クライアント</span><span class="sxs-lookup"><span data-stu-id="43a64-148">the communication client</span></span></param>
        <summary>
            <span data-ttu-id="43a64-149">クライアントがまだ有効な場合に true を返します。</span><span class="sxs-lookup"><span data-stu-id="43a64-149">Returns true if the client is still valid.</span></span> <span data-ttu-id="43a64-150">接続指向トランスポートでは、クライアントがサービスに接続していないことを示すために、このメソッドを使用できます。</span><span class="sxs-lookup"><span data-stu-id="43a64-150">Connection oriented transports can use this method to indicate that the client is no longer connected to the service.</span></span>
            </summary>
        <returns><span data-ttu-id="43a64-151">クライアントは、有効な場合は false をそれ以外の場合は true</span><span class="sxs-lookup"><span data-stu-id="43a64-151">true if the client is valid, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (string endpoint, TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(string endpoint, !TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (endpoint As String, client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : string * 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient (endpoint, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="43a64-152">接続されているクライアントを考えて、予期されるエンドポイントを指定します</span><span class="sxs-lookup"><span data-stu-id="43a64-152">Specifies the expected endpoint to which we think the client is connected to</span></span></param>
        <param name="client"><span data-ttu-id="43a64-153">通信クライアント</span><span class="sxs-lookup"><span data-stu-id="43a64-153">the communication client</span></span></param>
        <summary>
            <span data-ttu-id="43a64-154">クライアントがまだ有効であり、パラメーターで指定されたエンドポイントに接続されている場合に true を返します。</span><span class="sxs-lookup"><span data-stu-id="43a64-154">Returns true if the client is still valid and connected to the endpoint specified in the parameter.</span></span>
            </summary>
        <returns><span data-ttu-id="43a64-155">クライアントは、有効な場合は false をそれ以外の場合は true</span><span class="sxs-lookup"><span data-stu-id="43a64-155">true if the client is valid, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>