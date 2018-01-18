<Type Name="IActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory">
  <TypeSignature Language="C#" Value="public interface IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type IActorProxyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b618-101">アクター プロキシ ファクトリ クラスを作成するメソッドを含むインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="1b618-101">Defines the interface containing methods to create actor proxy factory class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="1b618-102">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1b618-102">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="1b618-103">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="1b618-103">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="serviceUri"><span data-ttu-id="1b618-104">アクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="1b618-104">Uri of the actor service.</span></span></param>
        <param name="actorId"><span data-ttu-id="1b618-105">プロキシのアクター オブジェクトのアクターの Id です。</span><span class="sxs-lookup"><span data-stu-id="1b618-105">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="1b618-106">このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</span><span class="sxs-lookup"><span data-stu-id="1b618-106">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1b618-107">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="1b618-107">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1b618-108">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1b618-108">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b618-109">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b618-109">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1b618-110">IActorProxy および TActorInterface を実装するアクター プロキシ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1b618-110">An actor proxy object that implements IActorProxy and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="1b618-111">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1b618-111">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="1b618-112">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="1b618-112">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="1b618-113">プロキシのアクター オブジェクトのアクターの Id です。</span><span class="sxs-lookup"><span data-stu-id="1b618-113">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="1b618-114">このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</span><span class="sxs-lookup"><span data-stu-id="1b618-114">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="1b618-115">アクター オブジェクトをホストするアクター サービスを含む Service Fabric アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b618-115">Name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="1b618-116">このパラメーターは、クライアントがその同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることはできます。</span><span class="sxs-lookup"><span data-stu-id="1b618-116">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="1b618-117">詳細については、「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b618-117">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="1b618-118">Service Fabric サービスによって構成されたとおりの名前<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクターの実装にします。</span><span class="sxs-lookup"><span data-stu-id="1b618-118">Name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="1b618-119">既定では、サービスの名前は、アクター インターフェイスの名前から派生します。</span><span class="sxs-lookup"><span data-stu-id="1b618-119">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="1b618-120">ただし<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />はアクターが 1 つ以上にアクター インターフェイスを実装するか、serviceName の決定は自動的に加えられることはできません、アクター インターフェイスが別のアクター インターフェイスから派生した場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="1b618-120">However <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interfaces or an actor interface derives from another actor interface as the determination of the serviceName cannot be made automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="1b618-121">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="1b618-121">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1b618-122">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1b618-122">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b618-123">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b618-123">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1b618-124">IActorProxy および TActorInterface を実装するアクター プロキシ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1b618-124">An actor proxy object that implements IActorProxy and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface"><span data-ttu-id="1b618-125">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1b618-125">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1b618-126">接続するアクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="1b618-126">Uri of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1b618-127">アクターの id です。</span><span class="sxs-lookup"><span data-stu-id="1b618-127">Id of the actor.</span></span> <span data-ttu-id="1b618-128">作成されたプロキシは、この id を持つアクターをホストするアクター サービスのパーティションに接続されます。</span><span class="sxs-lookup"><span data-stu-id="1b618-128">The created proxy will be connected to the partition of the actor service hosting actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1b618-129">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="1b618-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1b618-130">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1b618-130">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b618-131">指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b618-131">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1b618-132">IServiceProxy および TServiceInterface を実装するサービス プロキシ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1b618-132">A service proxy object that implements IServiceProxy and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface"><span data-ttu-id="1b618-133">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1b618-133">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1b618-134">接続するアクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="1b618-134">Uri of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1b618-135">接続するアクター サービス パーティションのキー。</span><span class="sxs-lookup"><span data-stu-id="1b618-135">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1b618-136">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="1b618-136">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1b618-137">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1b618-137">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b618-138">指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b618-138">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1b618-139">IServiceProxy および TServiceInterface を実装するサービス プロキシ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1b618-139">A service proxy object that implements IServiceProxy and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>