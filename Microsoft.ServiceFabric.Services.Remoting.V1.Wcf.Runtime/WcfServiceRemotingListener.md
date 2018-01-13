<Type Name="WcfServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="54131-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレスおよびステートフルなサービスのインターフェイスのリモート処理を提供する Windows Communication Foundation を使用します。</span><span class="sxs-lookup"><span data-stu-id="54131-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses Windows Communication Foundation to provide interface remoting for stateless and stateful services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = &quot;ServiceEndpoint&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, serviceImplementation, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="54131-102">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="54131-102">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="54131-103">サービス実装オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54131-103">The service implementation object.</span></span></param>
        <param name="listenerBinding"><span data-ttu-id="54131-104">リスナーに対して使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="54131-104">WCF binding to use for the listener.</span></span> <span data-ttu-id="54131-105">場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。</span><span class="sxs-lookup"><span data-stu-id="54131-105">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <param name="endpointResourceName"><span data-ttu-id="54131-106">アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="54131-106">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="54131-107">EndpointResourceName が指定されているか null でない場合は、既定値"ServiceEndpoint"が使用されます。</span><span class="sxs-lookup"><span data-stu-id="54131-107">If the endpointResourceName is not specified or null, the default value "ServiceEndpoint" is used.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54131-108">サービスのリモート処理のリスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="54131-108">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="54131-109">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="54131-109">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="messageHandler"><span data-ttu-id="54131-110">リモート処理のメッセージの受信と処理ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="54131-110">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="54131-111">メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。</span><span class="sxs-lookup"><span data-stu-id="54131-111">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="listenerBinding"><span data-ttu-id="54131-112">リスナーに対して使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="54131-112">WCF binding to use for the listener.</span></span> <span data-ttu-id="54131-113">場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="54131-113">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
            </param>
        <param name="address"><span data-ttu-id="54131-114">WCF のリスナーを使用するエンドポイント アドレス。</span><span class="sxs-lookup"><span data-stu-id="54131-114">The endpoint address to use for the WCF listener.</span></span> <span data-ttu-id="54131-115">指定しない場合、"ServiceEndpoint"サービス マニフェストで定義されているをという名前の既定のエンドポイント リソースを使用して、エンドポイント アドレスが作成された指定されているか null です。</span><span class="sxs-lookup"><span data-stu-id="54131-115">If not specified or null, the endpoint address is created using the default endpoint resource named "ServiceEndpoint" defined in the service manifest.</span></span> 
            </param>
        <summary>
            <span data-ttu-id="54131-116">サービスのリモート処理のリスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="54131-116">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = &quot;ServiceEndpoint&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="54131-117">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="54131-117">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="messageHandler"><span data-ttu-id="54131-118">リモート処理のメッセージの受信と処理ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="54131-118">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="54131-119">メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。</span><span class="sxs-lookup"><span data-stu-id="54131-119">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="listenerBinding"><span data-ttu-id="54131-120">リスナーに対して使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="54131-120">WCF binding to use for the listener.</span></span> <span data-ttu-id="54131-121">場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。</span><span class="sxs-lookup"><span data-stu-id="54131-121">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <param name="endpointResourceName"><span data-ttu-id="54131-122">アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="54131-122">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="54131-123">EndpointResourceName が指定されていないか、null、既定値"ServiceEndpoint"が使用されます。</span><span class="sxs-lookup"><span data-stu-id="54131-123">If the endpointResourceName is not specified or it is null, the default value "ServiceEndpoint" is used.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54131-124">サービスのリモート処理のリスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="54131-124">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54131-125">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="54131-125">This method causes the communication listener to close.</span></span> <span data-ttu-id="54131-126">閉じる終了の状態は、このメソッドは、異常終了への移行。</span><span class="sxs-lookup"><span data-stu-id="54131-126">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="54131-127">このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。</span><span class="sxs-lookup"><span data-stu-id="54131-127">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="54131-128">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="54131-128">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="54131-129">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="54131-129">This method causes the communication listener to close.</span></span> <span data-ttu-id="54131-130">終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。</span><span class="sxs-lookup"><span data-stu-id="54131-130">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="54131-131">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="54131-131">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="54131-132">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="54131-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="54131-133">このメソッドによって、通信リスナーを開くことができません。</span><span class="sxs-lookup"><span data-stu-id="54131-133">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="54131-134">Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="54131-134">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="54131-135">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="54131-135">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="54131-136">タスクの結果は、エンドポイントの文字列です。</span><span class="sxs-lookup"><span data-stu-id="54131-136">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="54131-137">取得、<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。</span><span class="sxs-lookup"><span data-stu-id="54131-137">Gets the <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </summary>
        <value>
                <span data-ttu-id="54131-138">A<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。</span><span class="sxs-lookup"><span data-stu-id="54131-138">A <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </value>
        <remarks>
                <span data-ttu-id="54131-139">サービス ホストは、そのコンス トラクターでリスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="54131-139">The service host is created by the listener in it's constructor.</span></span> <span data-ttu-id="54131-140">使用して、ランタイムによってこのような通信する前にリスナーが開かれました<see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />メソッドでは、このプロパティを介してアクセスすると、サービス ホストをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="54131-140">Before this communication listener is opened by the runtime via <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> method, the service host can be customized by accessing it via this property.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>