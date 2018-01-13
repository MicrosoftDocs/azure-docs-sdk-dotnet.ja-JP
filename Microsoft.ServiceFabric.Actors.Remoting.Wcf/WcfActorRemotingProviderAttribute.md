<Type Name="WcfActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public sealed class WcfActorRemotingProviderAttribute : Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WcfActorRemotingProviderAttribute extends Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WcfActorRemotingProviderAttribute&#xA;Inherits ActorRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type WcfActorRemotingProviderAttribute = class&#xA;    inherit ActorRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                <span data-ttu-id="86b00-101">リモート処理の既定のプロバイダーとしてのアクターの WCF を設定します。</span><span class="sxs-lookup"><span data-stu-id="86b00-101">Sets WCF as the default remoting provider for actors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="86b00-102">作成、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute" />これは、アクターのリモート処理の既定のプロバイダーとしての WCF の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="86b00-102">Creates a <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute" /> which can be used to set WCF as the default remoting provider for actors.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long CloseTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property CloseTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.CloseTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="86b00-103">取得または (ミリ秒) のメッセージ、接続を中止する前に、接続のドレインを待機する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="86b00-103">Gets or Sets time to wait in milliseconds for messages to drain on the connections before aborting the connection.</span></span> 
            </summary>
        <value>
                <span data-ttu-id="86b00-104">(ミリ秒) のメッセージ、接続を中止する前に、接続のドレインを待機する時間です。</span><span class="sxs-lookup"><span data-stu-id="86b00-104">Time to wait in milliseconds for messages to drain on the connections before aborting the connection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                <span data-ttu-id="86b00-105">クライアントの実装がコールバックをディスパッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="86b00-105">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="86b00-106">リモートのアクター インターフェイスへの接続にサービスのリモート処理クライアント ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-106">Creates a service remoting client factory to connect to the remoted actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="86b00-107">A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-107">A <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> to generate actor proxy to talk to the actor over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                <span data-ttu-id="86b00-108">クライアントの実装がコールバックをディスパッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="86b00-108">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="86b00-109">リモート アクター インターフェイスへの接続に V2 サービス リモート処理クライアント ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-109">Creates a V2 service remoting client factory to connect to the remoted actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="86b00-110">A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-110">A <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> to generate actor proxy to talk to the actor over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                <span data-ttu-id="86b00-111">リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="86b00-111">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
                <span data-ttu-id="86b00-112">リモート処理用のサービスのリモート処理リスナー アクター インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-112">Creates a service remoting listener for remoting the actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="86b00-113"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。</span><span class="sxs-lookup"><span data-stu-id="86b00-113">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified actor service.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                <span data-ttu-id="86b00-114">リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="86b00-114">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
                <span data-ttu-id="86b00-115">リモート処理の V2 サービス リモート処理リスナー アクター インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="86b00-115">Creates a V2 service remoting listener for remoting the actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="86b00-116"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。</span><span class="sxs-lookup"><span data-stu-id="86b00-116">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified actor service.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86b00-117">取得またはリモート処理のメッセージの最大サイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="86b00-117">Gets or Sets the maximum size of the remoting message in bytes.</span></span>
            <span data-ttu-id="86b00-118">このプロパティの値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="86b00-118">If value for this property is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
            </summary>
        <value>
                <span data-ttu-id="86b00-119">バイト単位でリモート処理のメッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="86b00-119">The maximum size of the remoting message in bytes.</span></span> <span data-ttu-id="86b00-120">この値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。</span><span class="sxs-lookup"><span data-stu-id="86b00-120">If this value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long OpenTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OpenTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OpenTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="86b00-121">取得または接続を開く (ミリ秒) 待機する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="86b00-121">Gets or Sets time to wait in milliseconds for opening the connection.</span></span>
            </summary>
        <value>
                <span data-ttu-id="86b00-122">接続を開く (ミリ秒) 待機する時間です。</span><span class="sxs-lookup"><span data-stu-id="86b00-122">Time to wait in milliseconds for opening the connection.</span></span> <span data-ttu-id="86b00-123">この値が指定されていないか、それが 0 より小さい、5000 ミリ秒の既定値が使用されます。</span><span class="sxs-lookup"><span data-stu-id="86b00-123">If this value is not specified or it is less than zero, default value of 5000 milliseconds is used.</span></span>
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>