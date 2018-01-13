<Type Name="FabricTransportActorRemotingClientFactory" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportActorRemotingClientFactory extends Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportActorRemotingClientFactory&#xA;Inherits FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type FabricTransportActorRemotingClientFactory = class&#xA;    inherit FabricTransportServiceRemotingClientFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b522a-101"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />ファブリック TCP トランスポートを使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />経由でリモート処理は実行されているインターフェイスでアクターと通信する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />です。</span><span class="sxs-lookup"><span data-stu-id="b522a-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that uses Fabric TCP transport to create <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" /> that communicate with actors over interfaces that are remoted via <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (callbackClient As IServiceRemotingCallbackClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory callbackClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                <span data-ttu-id="b522a-102">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b522a-102">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b522a-103">ファブリック トランスポート ベースのアクターのリモート処理クライアント ファクトリを構築します。</span><span class="sxs-lookup"><span data-stu-id="b522a-103">Constructs a fabric transport based actor remoting client factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings fabricTransportRemotingSettings, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings fabricTransportRemotingSettings, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory (fabricTransportRemotingSettings, callbackClient, servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricTransportRemotingSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fabricTransportRemotingSettings">
                <span data-ttu-id="b522a-104">ファブリック トランスポートの設定。</span><span class="sxs-lookup"><span data-stu-id="b522a-104">The settings for the fabric transport.</span></span> <span data-ttu-id="b522a-105">場合は、設定は、セキュリティなしで指定された、または null の既定の設定ではありません。</span><span class="sxs-lookup"><span data-stu-id="b522a-105">If the settings are not provided or null, default settings with no security.</span></span>
                </param>
        <param name="callbackClient">
                <span data-ttu-id="b522a-106">サービスからのコールバックを受信するコールバック クライアント。</span><span class="sxs-lookup"><span data-stu-id="b522a-106">The callback client that receives the callbacks from the service.</span></span>
            </param>
        <param name="servicePartitionResolver">
                <span data-ttu-id="b522a-107">サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。</span><span class="sxs-lookup"><span data-stu-id="b522a-107">Service partition resolver to resolve the service endpoints.</span></span> <span data-ttu-id="b522a-108">既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="b522a-108">If not specified, a default service partition resolver returned by <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> is used.</span></span>
                </param>
        <param name="exceptionHandlers">
                <span data-ttu-id="b522a-109">アクターと通信中に発生した例外を処理する例外ハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="b522a-109">Exception handlers to handle the exceptions encountered in communicating with the actor.</span></span>
            </param>
        <param name="traceId">
                <span data-ttu-id="b522a-110">このコンポーネントからのトレースを診断で使用する id。</span><span class="sxs-lookup"><span data-stu-id="b522a-110">Id to use in diagnostics traces from this component.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b522a-111">ファブリック トランスポート ベースのアクターのリモート処理クライアント ファクトリを構築します。</span><span class="sxs-lookup"><span data-stu-id="b522a-111">Constructs a fabric transport based actor remoting client factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>