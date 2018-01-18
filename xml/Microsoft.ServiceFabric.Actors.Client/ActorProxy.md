<Type Name="ActorProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxy">
  <TypeSignature Language="C#" Value="public abstract class ActorProxy : Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase, Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorProxy extends Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase implements class Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorProxy&#xA;Inherits ProxyBase&#xA;Implements IActorProxy" />
  <TypeSignature Language="F#" Value="type ActorProxy = class&#xA;    inherit ProxyBase&#xA;    interface IActorProxy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c3a3c-101">プロキシを実装するアクターのリモート オブジェクトへの基本実装を提供<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-101">Provides the base implementation for the proxy to the remote actor objects implementing <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> interfaces.</span></span>
            <span data-ttu-id="c3a3c-102">クライアントのアクターとアクターのアクターの通信に使用されるプロキシ オブジェクトを使用できます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-102">The proxy object can be used used for client-to-actor and actor-to-actor communication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3a3c-103">ActorProxy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-103">Initializes a new instance of the ActorProxy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a3c-104">取得<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-104">Gets <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span>
            </summary>
        <value>
          <span data-ttu-id="c3a3c-105"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-105"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClient As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClient : Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a3c-106">取得、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しているインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-106">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> interface that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="c3a3c-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClientV2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClientV2 As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClientV2 : Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a3c-108">取得、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しているインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-108">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> interface that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="c3a3c-109"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-109"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, Uri serviceUri, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Uri serviceUri, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.Uri,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * Uri * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, serviceUri, listenerName)" />
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
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="c3a3c-110">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-110">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="c3a3c-111">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-111">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="c3a3c-112">プロキシのアクター オブジェクトのアクターの Id です。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-112">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="c3a3c-113">このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-113">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="serviceUri"><span data-ttu-id="c3a3c-114">アクター サービスの Uri。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-114">Uri of the actor service.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="c3a3c-115">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-115">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="c3a3c-116">複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-116">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a3c-117">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-117">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="c3a3c-118">実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-118">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, applicationName, serviceName, listenerName)" />
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
            <span data-ttu-id="c3a3c-119">リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-119">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="c3a3c-120">返されるプロキシ オブジェクトでは、このインターフェイスを実装します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-120">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="c3a3c-121">プロキシ アクター オブジェクトのアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-121">The actor ID of the proxy actor object.</span></span> <span data-ttu-id="c3a3c-122">このプロキシに対してメソッドを呼び出すと、この ID に置き換えます。 アクターに送信される要求</span><span class="sxs-lookup"><span data-stu-id="c3a3c-122">Methods called on this proxy will result in requests being sent to the actor with this ID.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="c3a3c-123">アクター オブジェクトをホストするアクター サービスを含む Service Fabric アプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-123">The name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="c3a3c-124">このパラメーターは、クライアントがその同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることはできます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-124">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="c3a3c-125">詳細については、「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-125">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="c3a3c-126">Service Fabric サービスによって構成されたとおりの名前<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクターの実装にします。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-126">The name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="c3a3c-127">既定では、サービスの名前は、アクター インターフェイスの名前から派生します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-127">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="c3a3c-128">ただし、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />はアクターは、1 つ以上のアクター インターフェイスを実装するか、サービス名が自動的に確認できないので、アクター インターフェイスが別のアクター インターフェイスから派生した場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-128">However, <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interface or an actor interface derives from another actor interface since the service name cannot be determined automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="c3a3c-129">既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="c3a3c-130">ただし、複数のリスナーを使用するアクター サービスを構成することはできます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-130">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="c3a3c-131">このパラメーターに接続するリスナーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-131">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a3c-132">アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-132">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="c3a3c-133">実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-133">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c3a3c-134">ApplicationName パラメーターをクライアントが通信するために予定アクター サービスと同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-134">The applicationName parameter can be null if the client is running as part of the same Service Fabric application as the actor service it intends to communicate with.</span></span> <span data-ttu-id="c3a3c-135">アプリケーション名を決定するこの例では、 <see cref="T:System.Fabric.CodePackageActivationContext" />、呼び出すことで取得し、<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="c3a3c-135">In this case, the application name is determined from <see cref="T:System.Fabric.CodePackageActivationContext" />, and is obtained by calling the <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" /> property.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>