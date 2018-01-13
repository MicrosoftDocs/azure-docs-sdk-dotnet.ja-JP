<Type Name="WcfServiceRemotingClientFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingClientFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingClientFactory&#xA;Implements ICommunicationClientFactory(Of IServiceRemotingClient), IServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingClientFactory = class&#xA;    interface IServiceRemotingClientFactory&#xA;    interface ICommunicationClientFactory&lt;IServiceRemotingClient&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
            <span data-ttu-id="b0c39-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> Windows Communication Foundation を使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />経由でリモート処理は実行されているインターフェイス経由でステートレスおよびステートフルなサービスと通信<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />です。</span><span class="sxs-lookup"><span data-stu-id="b0c39-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that uses Windows Communication Foundation to create <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" /> to communicate with stateless and stateful services over interfaces that are remoted via <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingClientFactory (System.ServiceModel.Channels.Binding clientBinding = null, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null, Func&lt;System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,string,Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract&gt;&gt; createWcfClientFactory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId, class System.Func`6&lt;class System.ServiceModel.Channels.Binding, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver, string, class Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract, class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract&gt;&gt; createWcfClientFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.#ctor(System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,System.Func{System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory{Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientBinding As Binding = null, Optional callbackClient As IServiceRemotingCallbackClient = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null, Optional createWcfClientFactory As Func(Of Binding, IEnumerable(Of IExceptionHandler), IServicePartitionResolver, String, IServiceRemotingCallbackContract, WcfCommunicationClientFactory(Of IServiceRemotingContract)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory : System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string * Func&lt;System.ServiceModel.Channels.Binding, seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver, string, Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract, Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract&gt;&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory (clientBinding, callbackClient, exceptionHandlers, servicePartitionResolver, traceId, createWcfClientFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
        <Parameter Name="createWcfClientFactory" Type="System.Func&lt;System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                <span data-ttu-id="b0c39-102">クライアントに使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="b0c39-102">WCF binding to use for the client.</span></span> <span data-ttu-id="b0c39-103">クライアントのバインディングが指定されていないか、null、既定のクライアントのバインドを作成を使用して場合<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。</span><span class="sxs-lookup"><span data-stu-id="b0c39-103">If the client binding is not specified or null, a default client binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
                </param>
        <param name="callbackClient">
                <span data-ttu-id="b0c39-104">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b0c39-104">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <param name="exceptionHandlers">
                <span data-ttu-id="b0c39-105">サービスと通信中に発生した例外を処理する例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b0c39-105">Exception handlers to handle the exceptions encountered in communicating with the service.</span></span>
            </param>
        <param name="servicePartitionResolver">
                <span data-ttu-id="b0c39-106">サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。</span><span class="sxs-lookup"><span data-stu-id="b0c39-106">Service partition resolver to resolve the service endpoints.</span></span> <span data-ttu-id="b0c39-107">既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-107">If not specified, a default service partition resolver returned by <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> is used.</span></span>
                </param>
        <param name="traceId">
                <span data-ttu-id="b0c39-108">このコンポーネントからのトレースを診断で使用する id。</span><span class="sxs-lookup"><span data-stu-id="b0c39-108">Id to use in diagnostics traces from this component.</span></span>
            </param>
        <param name="createWcfClientFactory">
                <span data-ttu-id="b0c39-109">デリゲートを作成する関数<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />を使用して、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract" />です。</span><span class="sxs-lookup"><span data-stu-id="b0c39-109">Delegate function that creates <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" /> using the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract" />.</span></span>
                </param>
        <summary>
                <span data-ttu-id="b0c39-110">サービスのリモート処理クライアントのファクトリを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="b0c39-110">Constructs a WCF based service remoting client factory.</span></span>
            </summary>
        <remarks>
                <span data-ttu-id="b0c39-111">このファクトリを使用して<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />と<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />だけでなく、コンス トラクターに指定された例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b0c39-111">This factory uses <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" /> and <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" /> in addition to the exception handlers supplied to the constructor.</span></span> 
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0c39-112">クライアントがサービス エンドポイントに接続されているときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b0c39-112">Event handler that is fired when a client is connected to the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0c39-113">クライアントがサービス エンドポイントから切断されているときに発生するイベント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="b0c39-113">Event handler that is fired when a client is disconnected from the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__9))</AttributeName>
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
        <param name="previousRsp"><span data-ttu-id="b0c39-114">以前の ResolvedServicePartition 値</span><span class="sxs-lookup"><span data-stu-id="b0c39-114">Previous ResolvedServicePartition value</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b0c39-115">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b0c39-115">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b0c39-116">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-116">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b0c39-117">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-117">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b0c39-118">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b0c39-118">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b0c39-119">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを再解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-119">Re-resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="b0c39-120">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b0c39-120">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b0c39-121">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b0c39-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b0c39-122">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b0c39-122">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__8))</AttributeName>
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
        <param name="serviceUri"><span data-ttu-id="b0c39-123">サービスの Uri を解決するのには</span><span class="sxs-lookup"><span data-stu-id="b0c39-123">Uri of the service to resolve</span></span></param>
        <param name="partitionKey"><span data-ttu-id="b0c39-124">解決するのには、パーティションを識別するキー</span><span class="sxs-lookup"><span data-stu-id="b0c39-124">Key that identifies the partition to resolve</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="b0c39-125">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</span><span class="sxs-lookup"><span data-stu-id="b0c39-125">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="b0c39-126">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-126">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b0c39-127">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-127">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b0c39-128">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b0c39-128">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b0c39-129">1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-129">Resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="b0c39-130">フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="b0c39-130">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b0c39-131">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b0c39-131">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b0c39-132">タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b0c39-132">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.ReportOperationExceptionAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#ReportOperationExceptionAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
        <param name="client"><span data-ttu-id="b0c39-133">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="b0c39-133">Communication client</span></span></param>
        <param name="exceptionInformation"><span data-ttu-id="b0c39-134">サービスと通信中に発生した例外に関する情報。</span><span class="sxs-lookup"><span data-stu-id="b0c39-134">Information about exception that happened while communicating with the service.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b0c39-135">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-135">Specifies the retry policy that should be used for handling the reported exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b0c39-136">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="b0c39-136">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b0c39-137">サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。</span><span class="sxs-lookup"><span data-stu-id="b0c39-137">Handles the exceptions that occur in the CommunicationClient when sending a message to the Service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b0c39-138">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b0c39-138">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b0c39-139">タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />再試行ポリシーでこの例外の情報を提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b0c39-139">The result of the Task is a <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> object that provides information on retry policy for this exception.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>