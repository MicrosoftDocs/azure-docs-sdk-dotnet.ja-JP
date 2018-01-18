<Type Name="ActorServiceProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceProxy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceProxy" />
  <TypeSignature Language="F#" Value="type ActorServiceProxy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d322-101">Service Fabric クラスターで実行しているアクター サービスとの対話し、アクター サービス レベルの操作を実行するクライアントで使用されるプロキシを提供します。</span><span class="sxs-lookup"><span data-stu-id="1d322-101">Provides a Proxy used by clients to interact with the actor service running in a Service Fabric cluster and perform actor service level operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1d322-102"><see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1d322-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="1d322-103">接続するアクター サービスの URI。</span><span class="sxs-lookup"><span data-stu-id="1d322-103">The URI of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1d322-104">アクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="1d322-104">The ID of the actor.</span></span> <span data-ttu-id="1d322-105">作成されたプロキシはこの ID に置き換えます。 アクターをホストするアクター サービスのパーティションに接続します。</span><span class="sxs-lookup"><span data-stu-id="1d322-105">The created proxy will be connected to the partition of the actor service hosting the actor with this ID.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1d322-106">アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。</span><span class="sxs-lookup"><span data-stu-id="1d322-106">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1d322-107">ただし、複数のリスナーを使用するアクター サービスを構成することはできます。</span><span class="sxs-lookup"><span data-stu-id="1d322-107">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1d322-108">このパラメーターに接続するリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1d322-108">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d322-109">指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1d322-109">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1d322-110">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />と<see cref="T:Microsoft.ServiceFabric.Actors.IActorService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1d322-110">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> interfaces.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, long partitionKey, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As IActorService" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="1d322-111">接続するアクター サービスの URI。</span><span class="sxs-lookup"><span data-stu-id="1d322-111">The URI of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1d322-112">接続するアクター サービス パーティションのキー。</span><span class="sxs-lookup"><span data-stu-id="1d322-112">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1d322-113">アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。</span><span class="sxs-lookup"><span data-stu-id="1d322-113">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1d322-114">ただし、複数のリスナーを使用するアクター サービスを構成することはできます。</span><span class="sxs-lookup"><span data-stu-id="1d322-114">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1d322-115">このパラメーターに接続するリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1d322-115">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d322-116">指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1d322-116">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1d322-117">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />と<see cref="T:Microsoft.ServiceFabric.Actors.IActorService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1d322-117">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> interfaces.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
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
        <typeparam name="TServiceInterface"><span data-ttu-id="1d322-118">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1d322-118">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1d322-119">接続するアクター サービスの URI。</span><span class="sxs-lookup"><span data-stu-id="1d322-119">The URI of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1d322-120">アクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="1d322-120">The ID of the actor.</span></span> <span data-ttu-id="1d322-121">作成されたプロキシはこの ID に置き換えます。 アクターをホストするアクター サービスのパーティションに接続します。</span><span class="sxs-lookup"><span data-stu-id="1d322-121">The created proxy will be connected to the partition of the actor service hosting the actor with this ID.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1d322-122">アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。</span><span class="sxs-lookup"><span data-stu-id="1d322-122">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1d322-123">ただし、複数のリスナーを使用するアクター サービスを構成することはできます。</span><span class="sxs-lookup"><span data-stu-id="1d322-123">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1d322-124">このパラメーターに接続するリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1d322-124">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d322-125">指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1d322-125">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1d322-126">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</span><span class="sxs-lookup"><span data-stu-id="1d322-126">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
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
        <typeparam name="TServiceInterface"><span data-ttu-id="1d322-127">アクター サービスによって実装されるサービスのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="1d322-127">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1d322-128">接続するアクター サービスの URI。</span><span class="sxs-lookup"><span data-stu-id="1d322-128">The URI of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1d322-129">接続するアクター サービス パーティションのキー。</span><span class="sxs-lookup"><span data-stu-id="1d322-129">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1d322-130">アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。</span><span class="sxs-lookup"><span data-stu-id="1d322-130">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1d322-131">ただし、複数のリスナーを使用するアクター サービスを構成することはできます。</span><span class="sxs-lookup"><span data-stu-id="1d322-131">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1d322-132">このパラメーターに接続するリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1d322-132">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d322-133">指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="1d322-133">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1d322-134">実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</span><span class="sxs-lookup"><span data-stu-id="1d322-134">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>