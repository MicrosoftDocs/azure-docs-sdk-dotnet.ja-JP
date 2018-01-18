<Type Name="WcfActorServiceRemotingListener" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfActorServiceRemotingListener extends Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfActorServiceRemotingListener&#xA;Inherits WcfServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfActorServiceRemotingListener = class&#xA;    inherit WcfServiceRemotingListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5acd-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />アクター サービスのインターフェイスのリモート処理を提供する Windows Communication Foundation を使用します。</span><span class="sxs-lookup"><span data-stu-id="f5acd-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses Windows Communication Foundation to provide interface remoting for actor services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, System.ServiceModel.Channels.Binding listenerBinding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class System.ServiceModel.Channels.Binding listenerBinding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService * System.ServiceModel.Channels.Binding -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener (actorService, listenerBinding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="actorService"><span data-ttu-id="f5acd-102">アクター サービスです。</span><span class="sxs-lookup"><span data-stu-id="f5acd-102">The actor service.</span></span></param>
        <param name="listenerBinding"><span data-ttu-id="f5acd-103">リスナーに対して使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="f5acd-103">WCF binding to use for the listener.</span></span> <span data-ttu-id="f5acd-104">場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。</span><span class="sxs-lookup"><span data-stu-id="f5acd-104">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5acd-105">アクター リモート処理のリスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="f5acd-105">Constructs a WCF based actor remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener (serviceContext, serviceRemotingMessageHandler, serializationProvider, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceRemotingMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="f5acd-106">リモート処理のリスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="f5acd-106">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceRemotingMessageHandler"><span data-ttu-id="f5acd-107">リモート処理のメッセージの受信と処理ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5acd-107">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="f5acd-108">メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。</span><span class="sxs-lookup"><span data-stu-id="f5acd-108">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding"><span data-ttu-id="f5acd-109">リスナーに対して使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="f5acd-109">WCF binding to use for the listener.</span></span> <span data-ttu-id="f5acd-110">場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="f5acd-110">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
            </param>
        <param name="address"><span data-ttu-id="f5acd-111">WCF のリスナーを使用するエンドポイント アドレス。</span><span class="sxs-lookup"><span data-stu-id="f5acd-111">The endpoint address to use for the WCF listener.</span></span> <span data-ttu-id="f5acd-112">指定しない場合、"ServiceEndpoint"サービス マニフェストで定義されているをという名前の既定のエンドポイント リソースを使用して、エンドポイント アドレスが作成された指定されているか null です。</span><span class="sxs-lookup"><span data-stu-id="f5acd-112">If not specified or null, the endpoint address is created using the default endpoint resource named "ServiceEndpoint" defined in the service manifest.</span></span> 
            </param>
        <summary>
            <span data-ttu-id="f5acd-113">サービスのリモート処理のリスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="f5acd-113">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>