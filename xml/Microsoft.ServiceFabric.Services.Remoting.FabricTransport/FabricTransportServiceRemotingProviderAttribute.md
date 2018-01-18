<Type Name="FabricTransportServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="2043c-101">既定のサービスのリモート処理トランスポート プロバイダーとして、アセンブリ内のファブリック TCP トランスポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-101">Sets Fabric TCP transport as the default service remoting transport provider in the assembly.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2043c-102">構築、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />これは、既定のサービスのリモート処理トランスポート プロバイダーとして、アセンブリ内のファブリック TCP トランスポートの設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="2043c-102">Constructs a <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" /> which can be used to set Fabric TCP transport as the default service remoting transport provider in the assembly.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="2043c-103">取得またはミリ秒単位で接続タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-103">Gets or Sets the connect timeout in milliseconds.</span></span> <span data-ttu-id="2043c-104">この設定は、接続を確立する許可された最大時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-104">This settings specifies the maximum time allowed for the connection to be established.</span></span>
                </summary>
        <value>
                <span data-ttu-id="2043c-105">ミリ秒単位で接続タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="2043c-105">The connect timeout in Milliseconds.</span></span>
            </value>
        <remarks><span data-ttu-id="2043c-106">ConnectTimeout タイムアウトの既定値は、5 秒です。</span><span class="sxs-lookup"><span data-stu-id="2043c-106">Default Value for ConnectTimeout Timeout is 5 seconds.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
               <span data-ttu-id="2043c-107">コールバックをディスパッチする必要があるクライアントの実装です。</span><span class="sxs-lookup"><span data-stu-id="2043c-107">The client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="2043c-108">リモート サービス インターフェイスを介してサービスに接続の V1 サービス リモート処理クライアント ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-108">Creates a  V1 service remoting client factory for connecting to the service over remoted service interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="2043c-109">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />リモート アクター インターフェイス上でステートレスまたはステートフルなサービスと対話するサービスのプロキシを生成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-109">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to generate service proxy to talk to a stateless or stateful service over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">
               <span data-ttu-id="2043c-110">コールバックをディスパッチする必要があるクライアントの実装です。</span><span class="sxs-lookup"><span data-stu-id="2043c-110">The client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="2043c-111">リモート サービス インターフェイスを介してサービスに接続の V2 サービス リモート処理クライアント ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-111">Creates a  V2 service remoting client factory for connecting to the service over remoted service interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="2043c-112">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />リモート アクター インターフェイス上でステートレスまたはステートフルなサービスと対話するサービスのプロキシを生成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-112">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to generate service proxy to talk to a stateless or stateful service over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="2043c-113">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="2043c-113">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="2043c-114">サービス実装オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2043c-114">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="2043c-115">リモート処理用のサービスのリモート処理リスナーをサービス インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-115">Creates a service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="2043c-116">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />の指定されたサービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="2043c-116">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service implementation.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="2043c-117">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="2043c-117">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="2043c-118">サービス実装オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2043c-118">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="2043c-119">リモート処理サービス インターフェイスの V2 サービス リモート処理リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="2043c-119">Creates a V2 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="2043c-120">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />の指定されたサービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="2043c-120">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service implementation.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="2043c-121">取得またはキープ アライブ タイムアウトを秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-121">Gets or Sets the keep alive timeout in seconds.</span></span> <span data-ttu-id="2043c-122">この設定は、クライアントとサービスがしばらくアイドル状態がある場合、接続を閉じているロード バランサーを使用して接続しているときシナリオで役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2043c-122">This settings is useful in the scenario when the client and service are connected via load balancer that closes the connection if it is idle for some time.</span></span>
                <span data-ttu-id="2043c-123">かどうかキープ アライブ タイムアウトが構成されている、接続が維持されるその間隔で ping メッセージを送信しています。</span><span class="sxs-lookup"><span data-stu-id="2043c-123">If keep alive timeout is configured, the connection will be kept alive by sending ping messages at that interval.</span></span>
                </summary>
        <value>
                <span data-ttu-id="2043c-124">秒単位でキープ アライブ タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="2043c-124">The keep alive timeout in seconds.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="2043c-125">取得またはリモート処理のメッセージの最大サイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-125">Gets or Sets the maximum size of the remoting message in bytes.</span></span>
                <span data-ttu-id="2043c-126">このプロパティの値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="2043c-126">If value for this property is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </summary>
        <value>
                <span data-ttu-id="2043c-127">バイト単位でリモート処理のメッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="2043c-127">The maximum size of the remoting message in bytes.</span></span> <span data-ttu-id="2043c-128">この値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="2043c-128">If this value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long OperationTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OperationTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="2043c-129">取得または操作のタイムアウトを秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="2043c-129">Gets or Sets the operation timeout in seconds.</span></span> <span data-ttu-id="2043c-130">指定された時間で操作が完了していない場合それがタイムアウトします。既定では、例外ハンドラーの<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />例外を定期的に再試行します。</span><span class="sxs-lookup"><span data-stu-id="2043c-130">If the operation is not completed in the specified time, it will be timed out. By default, exception handler of <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> retries the timed out exception.</span></span> <span data-ttu-id="2043c-131">お勧めを変更する操作のタイムアウトの既定値からします。</span><span class="sxs-lookup"><span data-stu-id="2043c-131">It is recommended to not change the operation timeout from it's default value.</span></span> 
                </summary>
        <value>
                <span data-ttu-id="2043c-132">操作のタイムアウト (秒)。</span><span class="sxs-lookup"><span data-stu-id="2043c-132">The operation timeout in seconds.</span></span> <span data-ttu-id="2043c-133">指定またはしていない場合、既定の操作よりも小さいタイムアウトの最大値を使用します。</span><span class="sxs-lookup"><span data-stu-id="2043c-133">If not specified or less than zero, default operation timeout of maximum value is used.</span></span> 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>