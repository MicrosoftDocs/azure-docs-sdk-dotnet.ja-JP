<Type Name="FabricTransportActorServiceRemotingListener" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class FabricTransportActorServiceRemotingListener : Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportActorServiceRemotingListener extends Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportActorServiceRemotingListener&#xA;Inherits FabricTransportServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type FabricTransportActorServiceRemotingListener = class&#xA;    inherit FabricTransportServiceRemotingListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
                <span data-ttu-id="60a8b-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />アクター サービス用のアクターとサービスのインターフェイスのリモート処理を提供するファブリック TCP トランスポートを使用します。</span><span class="sxs-lookup"><span data-stu-id="60a8b-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses fabric TCP transport to provide remoting of actor and service interfaces for actor service.</span></span>
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener (actorService, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="actorService">
                <span data-ttu-id="60a8b-102">アクター サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="60a8b-102">The implementation of the actor service.</span></span>
            </param>
        <param name="listenerSettings">
                <span data-ttu-id="60a8b-103">リスナーで使用する設定。</span><span class="sxs-lookup"><span data-stu-id="60a8b-103">The settings to use for the listener.</span></span>
            </param>
        <summary>
                <span data-ttu-id="60a8b-104">ファブリック TCP ベース トランスポート サービス リモート処理のリスナーを指定されたアクター サービスを構築します。</span><span class="sxs-lookup"><span data-stu-id="60a8b-104">Construct a fabric TCP transport based service remoting listener for the specified actor service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener (serviceContext, messageHandler, listenerSettings, serializationProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="60a8b-105">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="60a8b-105">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="messageHandler">
                <span data-ttu-id="60a8b-106">リモート処理のメッセージを処理するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="60a8b-106">The handler for processing remoting messages.</span></span> <span data-ttu-id="60a8b-107">メッセージは、受信したリスナーに送りますをこのハンドラーにします。</span><span class="sxs-lookup"><span data-stu-id="60a8b-107">As the messages are received, the listener delivers them to this handler.</span></span>
                </param>
        <param name="listenerSettings"></param>
        <param name="serializationProvider"></param>
        <summary>
                <span data-ttu-id="60a8b-108">ファブリック TCP ベース トランスポート サービス リモート処理のリスナーを指定されたアクター サービスを構築します。</span><span class="sxs-lookup"><span data-stu-id="60a8b-108">Construct a fabric TCP transport based service remoting listener for the specified actor service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>