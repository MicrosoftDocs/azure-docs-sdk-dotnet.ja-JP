<Type Name="WcfActorRemotingClientFactory" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class WcfActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfActorRemotingClientFactory extends Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfActorRemotingClientFactory&#xA;Inherits WcfServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type WcfActorRemotingClientFactory = class&#xA;    inherit WcfServiceRemotingClientFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
                <span data-ttu-id="b6718-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> Windows Communication Foundation を使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient" />アクター サービスと関係者によって、ホスト経由でリモート処理は、アクターとサービスのインターフェイスを使用して通信するために<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener" />です。</span><span class="sxs-lookup"><span data-stu-id="b6718-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> that uses Windows Communication Foundation to create <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient" /> to communicate with an actor service and actors hosted by it, using actor and service interfaces that are remoted via <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Runtime.WcfActorServiceRemotingListener" />.</span></span>
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (callbackClient As IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory callbackClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                <span data-ttu-id="b6718-102">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b6718-102">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <summary>
                <span data-ttu-id="b6718-103">アクター リモート処理のファクトリを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="b6718-103">Constructs a WCF based actor remoting factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingClientFactory (System.ServiceModel.Channels.Binding clientBinding, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory.#ctor(System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientBinding As Binding, callbackClient As IServiceRemotingCallbackMessageHandler, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null, Optional serializationProvider As IServiceRemotingMessageSerializationProvider = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory : System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory (clientBinding, callbackClient, exceptionHandlers, servicePartitionResolver, traceId, serializationProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                <span data-ttu-id="b6718-104">クライアントに使用する WCF バインドします。</span><span class="sxs-lookup"><span data-stu-id="b6718-104">WCF binding to use for the client.</span></span> <span data-ttu-id="b6718-105">使用して、バインディングの既定のクライアントを作成するクライアントのバインディングが null の場合<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。</span><span class="sxs-lookup"><span data-stu-id="b6718-105">If the client binding is null, a default client binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
                </param>
        <param name="callbackClient">
                <span data-ttu-id="b6718-106">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b6718-106">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <param name="exceptionHandlers">
                <span data-ttu-id="b6718-107">サービスと通信中に発生した例外を処理する例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b6718-107">Exception handlers to handle the exceptions encountered in communicating with the service.</span></span>
            </param>
        <param name="servicePartitionResolver">
                <span data-ttu-id="b6718-108">サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。</span><span class="sxs-lookup"><span data-stu-id="b6718-108">Service partition resolver to resolve the service endpoints.</span></span> <span data-ttu-id="b6718-109">既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="b6718-109">If not specified, a default service partition resolver returned by <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> is used.</span></span>
                </param>
        <param name="traceId">
                <span data-ttu-id="b6718-110">このコンポーネントからのトレースを診断で使用する id。</span><span class="sxs-lookup"><span data-stu-id="b6718-110">Id to use in diagnostics traces from this component.</span></span>
            </param>
        <param name="serializationProvider"></param>
        <summary>
                <span data-ttu-id="b6718-111">アクター リモート処理のファクトリを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="b6718-111">Constructs a WCF based actor remoting factory.</span></span>
            </summary>
        <remarks>
                <span data-ttu-id="b6718-112">このファクトリを使用して<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />、 <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />、だけでなく、コンス トラクターに指定された例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b6718-112">This factory uses <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />, <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />, in addition to the exception handlers supplied to the constructor.</span></span> 
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>