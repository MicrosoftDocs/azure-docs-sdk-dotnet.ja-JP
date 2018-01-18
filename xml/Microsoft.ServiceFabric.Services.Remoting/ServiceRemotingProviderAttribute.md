<Type Name="ServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ServiceRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ServiceRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="89efb-101">これは、サービス インターフェイスが定義されているし、アセンブリで使用されるリモート処理に使用する既定のサービスのリモート処理プロバイダーを設定する属性の基本データ型です。</span><span class="sxs-lookup"><span data-stu-id="89efb-101">This is a base type for attribute that sets the default service remoting provider to use for remoting the service interfaces defined and used in the assembly.</span></span>
            </summary>
    <remarks>
      <para>
                <span data-ttu-id="89efb-102">サービス側では、この属性の実装がルックアップ<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" />と<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" />、既定値を作成するランタイムのメソッド<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートフルおよびステートレス サービス。</span><span class="sxs-lookup"><span data-stu-id="89efb-102">On service side, implementation of this attribute is looked up by <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" /> and <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" /> methods on the runtime to create a default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the stateful and stateless services.</span></span> 
                </para>
      <para>
                <span data-ttu-id="89efb-103">クライアント側では、この属性の実装はルックアップ<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />、既定値を作成するコンス トラクター<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="89efb-103">On client side, implementation of this attribute is looked up by <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> constructor to create a default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> when it is not specified.</span></span>
                </para>
      <para>
                <span data-ttu-id="89efb-104">指定されたクライアント側に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />方法は、既定値を作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />だけが最初に、同じプロバイダーが使用するまで 1 回とため、プロバイダーの参照が行わします。</span><span class="sxs-lookup"><span data-stu-id="89efb-104">Note that on client side <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" /> method create a default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> once and hence the provider lookup happens only for the first time, after which the same provider is used.</span></span>
                </para>
      <para>
                <span data-ttu-id="89efb-105">この属性が検索される順序は、次のように: <list type="number"> <item>エントリで<see cref="T:System.Reflection.Assembly" />メソッドを呼び出すことによって取得<see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item>で、<see cref="T:System.Reflection.Assembly" />をリモート インターフェイスを定義しますどのリスナーまたはプロキシを作成しています。</item></list></span><span class="sxs-lookup"><span data-stu-id="89efb-105">The order in which this attribute is looked up is as follows: <list type="number"><item> In the entry <see cref="T:System.Reflection.Assembly" /> obtained by calling method <see cref="M:System.Reflection.Assembly.GetEntryAssembly" /></item><item> In the <see cref="T:System.Reflection.Assembly" /> that defines the remote interface for which listener or proxy is being created. </item></list></span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89efb-106">ServiceRemotingProviderAttribute クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89efb-106">Initializes a new instance of the ServiceRemotingProviderAttribute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
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
        <param name="callbackClient"><span data-ttu-id="89efb-107">クライアントの実装がコールバックをディスパッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="89efb-107">Client implementation where the callbacks should be dispatched.</span></span></param>
        <summary>
            <span data-ttu-id="89efb-108">使用できるサービスのリモート処理クライアント ファクトリを作成、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />サービスのリモート インターフェイスのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="89efb-108">Creates a service remoting client factory that can be used by the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> to create a proxy for the remoted interface of the service.</span></span>
            </summary>
        <returns><span data-ttu-id="89efb-109"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />。</span><span class="sxs-lookup"><span data-stu-id="89efb-109">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
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
        <param name="callbackMessageHandler"><span data-ttu-id="89efb-110">クライアントの実装がコールバックをディスパッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="89efb-110">Client implementation where the callbacks should be dispatched.</span></span></param>
        <summary>
            <span data-ttu-id="89efb-111">V2 サービス リモート処理クライアントのファクトリを作成して使用できる、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />サービスのリモート インターフェイスのプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="89efb-111">Creates a V2 service remoting client factory that can be used by the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> to create a proxy for the remoted interface of the service.</span></span>
            </summary>
        <returns><span data-ttu-id="89efb-112"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />。</span><span class="sxs-lookup"><span data-stu-id="89efb-112">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
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
        <param name="serviceContext"><span data-ttu-id="89efb-113">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="89efb-113">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="89efb-114">サービス実装オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="89efb-114">The service implementation object.</span></span></param>
        <summary>
            <span data-ttu-id="89efb-115">リモート処理サービス インターフェイスの V1 サービス リモート処理リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="89efb-115">Creates a V1 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="89efb-116"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたサービスのです。</span><span class="sxs-lookup"><span data-stu-id="89efb-116">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
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
        <param name="serviceContext"><span data-ttu-id="89efb-117">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="89efb-117">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="89efb-118">サービス実装オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="89efb-118">The service implementation object.</span></span></param>
        <summary>
            <span data-ttu-id="89efb-119">リモート処理サービス インターフェイスの V2 サービス リモート処理リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="89efb-119">Creates a V2 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="89efb-120"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたサービスのです。</span><span class="sxs-lookup"><span data-stu-id="89efb-120">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89efb-121">RemotingClient を使用して、V1 または V2 のリモート クライアントが使用されているかを決定します。</span><span class="sxs-lookup"><span data-stu-id="89efb-121">RemotingClient is used to determine where  V1 or V2 remoting Client is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89efb-122">RemotingListener を使用して、V1、V2 またはコンパクト モードにリスナーがある場合を決定します。</span><span class="sxs-lookup"><span data-stu-id="89efb-122">RemotingListener is used to determine where listener is in V1, V2 or Compact Mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>