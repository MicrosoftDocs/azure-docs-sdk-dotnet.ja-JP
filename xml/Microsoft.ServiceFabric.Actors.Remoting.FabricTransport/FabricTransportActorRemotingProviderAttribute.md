<Type Name="FabricTransportActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportActorRemotingProviderAttribute : Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportActorRemotingProviderAttribute extends Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportActorRemotingProviderAttribute&#xA;Inherits ActorRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportActorRemotingProviderAttribute = class&#xA;    inherit ActorRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
                <span data-ttu-id="e05b8-101">アクターの既定のリモート処理プロバイダーとしてのファブリック TCP トランスポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-101">Sets fabric TCP transport as the default remoting provider for the actors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e05b8-102">新しいインスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute" />、これは、アクターが、既定のリモート処理プロバイダーとしてファブリック TCP トランスポートの設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="e05b8-102">Instantiates a new <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute" />, which can be used to set fabric TCP transport as the default remoting provider for the actors.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="e05b8-103">取得またはミリ秒単位で接続タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-103">Gets or Sets the connect timeout in milliseconds.</span></span> <span data-ttu-id="e05b8-104">この設定は、接続を確立する許可された最大時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-104">This settings specifies the maximum time allowed for the connection to be established.</span></span>
                </summary>
        <value>
                <span data-ttu-id="e05b8-105">ミリ秒単位で接続タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="e05b8-105">The connect timeout in Milliseconds.</span></span>
            </value>
        <remarks><span data-ttu-id="e05b8-106">ConnectTimeout タイムアウトの既定値は、5 秒です。</span><span class="sxs-lookup"><span data-stu-id="e05b8-106">Default Value for ConnectTimeout Timeout is 5 seconds.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
                <span data-ttu-id="e05b8-107">クライアントの実装がコールバックをディスパッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e05b8-107">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="e05b8-108">リモートのアクター インターフェイスへの接続にサービスのリモート処理クライアント ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-108">Creates a service remoting client factory to connect to the remoted actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="e05b8-109">A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-109">A <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.ActorProxyFactory" /> to generate actor proxy to talk to the actor over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                <span data-ttu-id="e05b8-110">リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="e05b8-110">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
                <span data-ttu-id="e05b8-111">リモート処理用のサービスのリモート処理リスナー アクター インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-111">Creates a service remoting listener for remoting the actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="e05b8-112">A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。</span><span class="sxs-lookup"><span data-stu-id="e05b8-112">A <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified actor service.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                <span data-ttu-id="e05b8-113">リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="e05b8-113">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
                <span data-ttu-id="e05b8-114">リモート処理用のサービスのリモート処理リスナー アクター インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-114">Creates a service remoting listener for remoting the actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="e05b8-115">A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。</span><span class="sxs-lookup"><span data-stu-id="e05b8-115">A <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified actor service.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="e05b8-116">取得またはキープ アライブ タイムアウトを秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-116">Gets or Sets the keep alive timeout in seconds.</span></span> <span data-ttu-id="e05b8-117">この設定は、クライアントとサービスがしばらくアイドル状態がある場合、接続を閉じているロード バランサーを使用して接続しているときシナリオで役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e05b8-117">This settings is useful in the scenario when the client and service are connected via load balancer that closes the connection if it is idle for some time.</span></span>
                <span data-ttu-id="e05b8-118">かどうかキープ アライブ タイムアウトが構成されている、接続が維持されるその間隔で ping メッセージを送信しています。</span><span class="sxs-lookup"><span data-stu-id="e05b8-118">If keep alive timeout is configured, the connection will be kept alive by sending ping messages at that interval.</span></span>
                </summary>
        <value>
                <span data-ttu-id="e05b8-119">秒単位でキープ アライブ タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="e05b8-119">The keep alive timeout in seconds.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05b8-120">取得またはリモート処理のメッセージの最大サイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-120">Gets or Sets the maximum size of the remoting message in bytes.</span></span>
            <span data-ttu-id="e05b8-121">このプロパティの値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-121">If value for this property is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
            </summary>
        <value>
                <span data-ttu-id="e05b8-122">バイト単位でリモート処理のメッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="e05b8-122">The maximum size of the remoting message in bytes.</span></span> <span data-ttu-id="e05b8-123">この値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-123">If this value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long OperationTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OperationTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="e05b8-124">取得または操作のタイムアウトを秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-124">Gets or Sets the operation timeout in seconds.</span></span> <span data-ttu-id="e05b8-125">指定された時間で操作が完了していない場合それがタイムアウトします。既定では、FabricTransportServiceRemotingClientFactory の例外ハンドラー/&gt;例外を定期的に再試行します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-125">If the operation is not completed in the specified time, it will be timed out. By default, exception handler of FabricTransportServiceRemotingClientFactory /&gt; retries the timed out exception.</span></span> <span data-ttu-id="e05b8-126">お勧めを変更する操作のタイムアウトの既定値からします。</span><span class="sxs-lookup"><span data-stu-id="e05b8-126">It is recommended to not change the operation timeout from it's default value.</span></span> 
                </summary>
        <value>
                <span data-ttu-id="e05b8-127">操作のタイムアウト (秒)。</span><span class="sxs-lookup"><span data-stu-id="e05b8-127">The operation timeout in seconds.</span></span> <span data-ttu-id="e05b8-128">指定またはしていない場合、既定の操作よりも小さいタイムアウトの最大値を使用します。</span><span class="sxs-lookup"><span data-stu-id="e05b8-128">If not specified or less than zero, default operation timeout of maximum value is used.</span></span> 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>