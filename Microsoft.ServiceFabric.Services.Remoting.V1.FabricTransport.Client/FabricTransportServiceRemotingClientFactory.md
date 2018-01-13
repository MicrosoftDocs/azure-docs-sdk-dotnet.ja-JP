<Type Name="FabricTransportServiceRemotingClientFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingClientFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingClientFactory&#xA;Implements ICommunicationClientFactory(Of IServiceRemotingClient), IServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingClientFactory = class&#xA;    interface IServiceRemotingClientFactory&#xA;    interface ICommunicationClientFactory&lt;IServiceRemotingClient&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b1e66-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />ファブリック TCP トランスポートを使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />経由でリモート処理は実行されているインターフェイスでステートレスおよびステートフルなサービスと通信する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />です。</span><span class="sxs-lookup"><span data-stu-id="b1e66-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that uses Fabric TCP transport to create <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" /> that communicate with stateless and stateful services over interfaces that are remoted via <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings FabricTransportRemotingSettings = null, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings FabricTransportRemotingSettings, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory (FabricTransportRemotingSettings, callbackClient, servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="FabricTransportRemotingSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="FabricTransportRemotingSettings">
                <span data-ttu-id="b1e66-102">ファブリック トランスポートの設定。</span><span class="sxs-lookup"><span data-stu-id="b1e66-102">The settings for the fabric transport.</span></span> <span data-ttu-id="b1e66-103">場合は、設定は、セキュリティなしで指定された、または null の既定の設定ではありません。</span><span class="sxs-lookup"><span data-stu-id="b1e66-103">If the settings are not provided or null, default settings with no security.</span></span>
                </param>
        <param name="callbackClient">
                <span data-ttu-id="b1e66-104">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b1e66-104">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <param name="servicePartitionResolver">
                <span data-ttu-id="b1e66-105">サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。</span><span class="sxs-lookup"><span data-stu-id="b1e66-105">Service partition resolver to resolve the service endpoints.</span></span> <span data-ttu-id="b1e66-106">既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-106">If not specified, a default service partition resolver returned by <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> is used.</span></span>
                </param>
        <param name="exceptionHandlers">
                <span data-ttu-id="b1e66-107">サービスと通信中に発生した例外を処理する例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b1e66-107">Exception handlers to handle the exceptions encountered in communicating with the service.</span></span>
            </param>
        <param name="traceId">
                <span data-ttu-id="b1e66-108">このコンポーネントからのトレースを診断で使用する id。</span><span class="sxs-lookup"><span data-stu-id="b1e66-108">Id to use in diagnostics traces from this component.</span></span>
            </param>
        <summary>
                <span data-ttu-id="b1e66-109">ファブリック トランスポート ベースのサービスのリモート処理クライアント ファクトリを構築します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-109">Constructs a fabric transport based service remoting client factory.</span></span>
            </summary>
        <remarks>
                <span data-ttu-id="b1e66-110">このファクトリは、ファブリック TCP トランスポート レベルでの例外を処理する内部ファブリック トランスポート例外ハンドラーを使用し、 <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />、だけでなく、コンス トラクターに指定された例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b1e66-110">This factory uses an internal fabric transport exception handler to handle exceptions at the fabric TCP transport level and a <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />, in addition to the exception handlers supplied to the constructor.</span></span> 
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1e66-111">クライアントがサービス エンドポイントに接続されているときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b1e66-111">Event handler that is fired when a client is connected to the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1e66-112">クライアントがサービス エンドポイントから切断されているときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b1e66-112">Event handler that is fired when a client is disconnected from the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="b1e66-113">以前の ResolvedServicePartition 値</span><span class="sxs-lookup"><span data-stu-id="b1e66-113">Previous ResolvedServicePartition value</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b1e66-114">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b1e66-114">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b1e66-115">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-115">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b1e66-116">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-116">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b1e66-117">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b1e66-117">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b1e66-118">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを再解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-118">Re-resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span>
            <span data-ttu-id="b1e66-119">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b1e66-119">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1e66-120">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b1e66-120">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b1e66-121">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b1e66-121">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</ReturnType>
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
        <param name="serviceUri"><span data-ttu-id="b1e66-122">サービスの Uri を解決するのには</span><span class="sxs-lookup"><span data-stu-id="b1e66-122">Uri of the service to resolve</span></span></param>
        <param name="partitionKey"><span data-ttu-id="b1e66-123">解決するのには、パーティションを識別するキー</span><span class="sxs-lookup"><span data-stu-id="b1e66-123">Key that identifies the partition to resolve</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b1e66-124">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b1e66-124">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b1e66-125">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-125">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b1e66-126">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-126">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b1e66-127">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b1e66-127">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b1e66-128">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-128">Resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span>
            <span data-ttu-id="b1e66-129">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b1e66-129">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1e66-130">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b1e66-130">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b1e66-131">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b1e66-131">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.ReportOperationExceptionAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#ReportOperationExceptionAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="b1e66-132">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="b1e66-132">Communication client</span></span></param>
        <param name="exceptionInformation"><span data-ttu-id="b1e66-133">サービスと通信中に発生した例外に関する情報。</span><span class="sxs-lookup"><span data-stu-id="b1e66-133">Information about exception that happened while communicating with the service.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b1e66-134">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-134">Specifies the retry policy that should be used for handling the reported exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b1e66-135">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b1e66-135">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b1e66-136">サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。</span><span class="sxs-lookup"><span data-stu-id="b1e66-136">Handles the exceptions that occur in the CommunicationClient when sending a message to the Service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1e66-137">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b1e66-137">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b1e66-138">タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />再試行ポリシーでこの例外の情報を提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b1e66-138">The result of the Task is a <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> object that provides information on retry policy for this exception.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>