<Type Name="ActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory">
  <TypeSignature Language="C#" Value="public class ActorProxyFactory : Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorProxyFactory&#xA;Implements IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type ActorProxyFactory = class&#xA;    interface IActorProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="426cb-101">リモートのアクターのオブジェクトへのプロキシを作成するファクトリ クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="426cb-101">Represents a factory class to create a proxy to the remote actor objects.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings"><span data-ttu-id="426cb-102">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="426cb-102">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="426cb-103"><see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="426cb-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory"><span data-ttu-id="426cb-104">リモート処理の通信のクライアントのファクトリを作成するファクトリ メソッド。</span><span class="sxs-lookup"><span data-stu-id="426cb-104">Factory method to create remoting communication client factory.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="426cb-105">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="426cb-105">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="426cb-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />クラス V1 リモート処理クライアント ファクトリを使用します。</span><span class="sxs-lookup"><span data-stu-id="426cb-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class using V1 remoting Client Factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory"><span data-ttu-id="426cb-107">リモート処理の通信のクライアントのファクトリを作成するファクトリ メソッド。</span><span class="sxs-lookup"><span data-stu-id="426cb-107">Factory method to create remoting communication client factory.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="426cb-108">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="426cb-108">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="426cb-109">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />クラス V2 リモート処理クライアントのファクトリを使用します。</span><span class="sxs-lookup"><span data-stu-id="426cb-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class using V2 Remoting Client Factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="426cb-110">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="426cb-110">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="426cb-111">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="426cb-111">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="serviceUri"><span data-ttu-id="426cb-112">アクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="426cb-112">Uri of the actor service.</span></span></param>
        <param name="actorId"><span data-ttu-id="426cb-113">プロキシのアクター オブジェクトのアクターの Id です。</span><span class="sxs-lookup"><span data-stu-id="426cb-113">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="426cb-114">このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</span><span class="sxs-lookup"><span data-stu-id="426cb-114">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="426cb-115">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="426cb-115">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="426cb-116">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="426cb-116">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426cb-117">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="426cb-117">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="426cb-118">実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</span><span class="sxs-lookup"><span data-stu-id="426cb-118">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="426cb-119">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="426cb-119">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="426cb-120">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="426cb-120">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="426cb-121">プロキシのアクター オブジェクトのアクターの Id です。</span><span class="sxs-lookup"><span data-stu-id="426cb-121">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="426cb-122">このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</span><span class="sxs-lookup"><span data-stu-id="426cb-122">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="426cb-123">アクター オブジェクトをホストするアクター サービスを含む Service Fabric アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="426cb-123">Name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="426cb-124">このパラメーターは、クライアントがその同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることはできます。</span><span class="sxs-lookup"><span data-stu-id="426cb-124">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="426cb-125">詳細については、「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="426cb-125">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="426cb-126">Service Fabric サービスによって構成されたとおりの名前<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクターの実装にします。</span><span class="sxs-lookup"><span data-stu-id="426cb-126">Name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="426cb-127">既定では、サービスの名前は、アクター インターフェイスの名前から派生します。</span><span class="sxs-lookup"><span data-stu-id="426cb-127">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="426cb-128">ただし<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />はアクターが 1 つ以上にアクター インターフェイスを実装するか、serviceName の決定は自動的に加えられることはできません、アクター インターフェイスが別のアクター インターフェイスから派生した場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="426cb-128">However <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interfaces or an actor interface derives from another actor interface as the determination of the serviceName cannot be made automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="426cb-129">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="426cb-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="426cb-130">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="426cb-130">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426cb-131">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="426cb-131">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="426cb-132">実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</span><span class="sxs-lookup"><span data-stu-id="426cb-132">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
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
        <typeparam name="TServiceInterface"><span data-ttu-id="426cb-133">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="426cb-133">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="426cb-134">接続するアクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="426cb-134">Uri of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="426cb-135">アクターの id です。</span><span class="sxs-lookup"><span data-stu-id="426cb-135">Id of the actor.</span></span> <span data-ttu-id="426cb-136">作成されたプロキシは、この id を持つアクターをホストするアクター サービスのパーティションに接続されます。</span><span class="sxs-lookup"><span data-stu-id="426cb-136">The created proxy will be connected to the partition of the actor service hosting actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="426cb-137">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="426cb-137">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="426cb-138">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="426cb-138">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426cb-139">指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="426cb-139">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="426cb-140">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</span><span class="sxs-lookup"><span data-stu-id="426cb-140">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)</InterfaceMember>
      </Implements>
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
        <typeparam name="TServiceInterface"><span data-ttu-id="426cb-141">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="426cb-141">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="426cb-142">接続するアクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="426cb-142">Uri of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="426cb-143">接続するアクター サービス パーティションのキー。</span><span class="sxs-lookup"><span data-stu-id="426cb-143">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="426cb-144">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="426cb-144">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="426cb-145">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="426cb-145">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426cb-146">指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="426cb-146">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="426cb-147">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</span><span class="sxs-lookup"><span data-stu-id="426cb-147">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>