<Type Name="FabricTransportServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
                <span data-ttu-id="23c18-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレスおよびステートフルなサービスのインターフェイスのリモート処理を提供するファブリック TCP トランスポートを使用します。</span><span class="sxs-lookup"><span data-stu-id="23c18-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses fabric TCP transport to provide interface remoting for stateless and stateful services.</span></span>
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-102">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-102">The context of the service for which the remoting listener is being constructed.</span></span> 
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="23c18-103">サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。</span><span class="sxs-lookup"><span data-stu-id="23c18-103">The service implementation object used to construct <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> for message processing.</span></span>
                </param>
        <summary>
                <span data-ttu-id="23c18-104">既定値はファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="23c18-104">Constructs a fabric transport based service remoting listener with default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-105">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-105">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="messageHandler">
                <span data-ttu-id="23c18-106">リモート処理のメッセージを処理するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="23c18-106">The handler for processing remoting messages.</span></span> <span data-ttu-id="23c18-107">メッセージは、受信したリスナーに送りますをこのハンドラーにします。</span><span class="sxs-lookup"><span data-stu-id="23c18-107">As the messages are received, the listener delivers them to this handler.</span></span>
                </param>
        <summary>
                <span data-ttu-id="23c18-108">既定値はファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="23c18-108">Constructs a fabric transport based service remoting listener with default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-109">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-109">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="23c18-110">サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。</span><span class="sxs-lookup"><span data-stu-id="23c18-110">The service implementation object used to construct <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> for message processing.</span></span>
                </param>
        <param name="listenerSettings">
                <span data-ttu-id="23c18-111">リスナーの設定。</span><span class="sxs-lookup"><span data-stu-id="23c18-111">The settings for the listener.</span></span>
            </param>
        <summary>
                <span data-ttu-id="23c18-112">指定されたファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="23c18-112">Constructs a fabric transport based service remoting listener with the specified <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-113">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-113">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="23c18-114">サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。</span><span class="sxs-lookup"><span data-stu-id="23c18-114">The service implementation object used to construct <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> for message processing.</span></span>
                </param>
        <param name="listenerSettingsConfigSectionName">
               <span data-ttu-id="23c18-115">構成パッケージの構成セクションの名前では、リスナーの設定を定義するサービス マニフェストで"Config"という名前です。</span><span class="sxs-lookup"><span data-stu-id="23c18-115">The name of the configuration section in the configuration package named "Config" in the service manifest that defines the settings for the listener.</span></span> 
               </param>
        <summary>
                <span data-ttu-id="23c18-116">ファブリック トランスポート ベース サービスのリモート処理のリスナーが構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />構成セクションから読み込まれます。</span><span class="sxs-lookup"><span data-stu-id="23c18-116">Constructs a fabric transport based service remoting listener with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> loaded from configuration section.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-117">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-117">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="messageHandler">
                <span data-ttu-id="23c18-118">リモート処理のメッセージを処理するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="23c18-118">The handler for processing remoting messages.</span></span> <span data-ttu-id="23c18-119">メッセージは、受信したリスナーに送りますをこのハンドラーにします。</span><span class="sxs-lookup"><span data-stu-id="23c18-119">As the messages are received, the listener delivers them to this handler.</span></span>
                </param>
        <param name="listenerSettings">
                <span data-ttu-id="23c18-120">リスナーで使用する設定。</span><span class="sxs-lookup"><span data-stu-id="23c18-120">The settings to use for the listener.</span></span>
            </param>
        <summary>
                <span data-ttu-id="23c18-121">指定されたファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="23c18-121">Constructs a fabric transport based service remoting listener with the specified <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="23c18-122">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="23c18-122">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="messageHandler">
                <span data-ttu-id="23c18-123">リモート処理のメッセージを処理するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="23c18-123">The handler for processing remoting messages.</span></span> <span data-ttu-id="23c18-124">メッセージは、受信したリスナーに送りますをこのハンドラーにします。</span><span class="sxs-lookup"><span data-stu-id="23c18-124">As the messages are received, the listener delivers them to this handler.</span></span>
                </param>
        <param name="listenerSettingsConfigSectionName">
               <span data-ttu-id="23c18-125">構成パッケージの構成セクションの名前では、リスナーの設定を定義するサービス マニフェストで"Config"という名前です。</span><span class="sxs-lookup"><span data-stu-id="23c18-125">The name of the configuration section in the configuration package named "Config" in the service manifest that defines the settings for the listener.</span></span> 
               </param>
        <summary>
                <span data-ttu-id="23c18-126">ファブリック トランスポート ベース サービスのリモート処理のリスナーが構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />構成セクションから読み込まれます。</span><span class="sxs-lookup"><span data-stu-id="23c18-126">Constructs a fabric transport based service remoting listener with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> loaded from configuration section.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23c18-127">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="23c18-127">This method causes the communication listener to close.</span></span> <span data-ttu-id="23c18-128">閉じる終了の状態は、このメソッドは、異常終了への移行。</span><span class="sxs-lookup"><span data-stu-id="23c18-128">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="23c18-129">このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。</span><span class="sxs-lookup"><span data-stu-id="23c18-129">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="23c18-130">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="23c18-130">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="23c18-131">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="23c18-131">This method causes the communication listener to close.</span></span> <span data-ttu-id="23c18-132">終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。</span><span class="sxs-lookup"><span data-stu-id="23c18-132">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="23c18-133">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="23c18-133">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="23c18-134">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="23c18-134">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="23c18-135">このメソッドによって、通信リスナーを開くことができません。</span><span class="sxs-lookup"><span data-stu-id="23c18-135">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="23c18-136">Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="23c18-136">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="23c18-137">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="23c18-137">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="23c18-138">タスクの結果は、エンドポイントの文字列です。</span><span class="sxs-lookup"><span data-stu-id="23c18-138">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>