<Type Name="IServiceProxyFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory">
  <TypeSignature Language="C#" Value="public interface IServiceProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceProxyFactory" />
  <TypeSignature Language="F#" Value="type IServiceProxyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe285-101">指定されたサービスへのリモート通信にプロキシを作成するファクトリのインターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="fe285-101">Specifies the interface for the factory that creates proxies for remote communication to the specified service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iServiceProxyFactory.CreateServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">To be added.</typeparam>
        <param name="serviceUri">To be added.</param>
        <param name="partitionKey">To be added.</param>
        <param name="targetReplicaSelector">To be added.</param>
        <param name="listenerName">To be added.</param>
        <summary>
            <span data-ttu-id="fe285-102">サービスによって実装される TServiceInterface リモート インターフェイスを使用して、指定されたサービスと通信するプロキシを作成します。</span><span class="sxs-lookup"><span data-stu-id="fe285-102">Creates a proxy to communicate to the specified service using the remoted interface TServiceInterface that the service implements.</span></span>
            <span data-ttu-id="fe285-103"><typeparam name="TServiceInterface">リモート処理は実行されているインターフェイス。</typeparam><param name="serviceUri">サービスの Uri</param> 。<param name="partitionKey">サービス パーティションはこのサービス プロキシからの要求の処理を決定する、パーティション キーです。</param><param name="targetReplicaSelector">どのレプリカまたは、クライアントが接続するサービス パーティションのインスタンスを決定します</param>。<param name="listenerName">サービスに 1 つの通信リスナーがある場合、このパラメーターは省略可能です。サービスのエンドポイントがの形式は {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}。サービスは、複数のエンドポイントを公開するときにこのパラメーターは、リモート通信に使用するには、そのエンドポイントのうちを識別します。</param><returns>リモート処理は実行されているインターフェイスを実装するプロキシ。返されたオブジェクトでは、IServiceProxy インターフェイスも実装します。</returns></span><span class="sxs-lookup"><span data-stu-id="fe285-103"><typeparam name="TServiceInterface">The interface that is being remoted.</typeparam><param name="serviceUri">The Uri of the Service.</param><param name="partitionKey">The Partition key that determines which service partition is responsible for handling requests from this service proxy.</param><param name="targetReplicaSelector">Determines which replica or instance of the service partition the client should connect to.</param><param name="listenerName">This parameter is Optional if the service has a single communication listener. The endpoints from the service are of the form {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}. When the service exposes multiple endpoints, this parameter identifies which of those endpoints to use for the remoting communication. </param><returns>The proxy that implement the interface that is being remoted. The returned object also implement IServiceProxy interface.</returns></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>