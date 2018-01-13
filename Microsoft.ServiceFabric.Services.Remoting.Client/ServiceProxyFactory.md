<Type Name="ServiceProxyFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory">
  <TypeSignature Language="C#" Value="public class ServiceProxyFactory : Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceProxyFactory&#xA;Implements IServiceProxyFactory" />
  <TypeSignature Language="F#" Value="type ServiceProxyFactory = class&#xA;    interface IServiceProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            指定されたサービスへのリモート通信にプロキシを作成するファクトリを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings">To be added.</param>
        <summary>
            指定した retrysettings と既定 remotingClientFactory で ServiceProxyFactory をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">
            リモート処理クライアントのファクトリを作成するファクトリ メソッドを指定します。 リモート処理クライアント ファクトリがこれから取得したメソッドは、ServiceProxyFactory にキャッシュします。
            </param>
        <param name="retrySettings">このファクトリによって作成されたプロキシを使用する場合に発生する例外で使用する再試行ポリシーを指定します</param>
        <summary>
            指定した V1 リモート処理ファクトリと retrysettings ServiceProxyFactory をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">
            リモート処理クライアントのファクトリを作成するファクトリ メソッドを指定します。 リモート処理クライアント ファクトリがこれから取得したメソッドは、ServiceProxyFactory にキャッシュします。
            </param>
        <param name="retrySettings">このファクトリによって作成されたプロキシを使用する場合に発生する例外で使用する再試行ポリシーを指定します</param>
        <summary>
            指定した V2 リモート処理ファクトリと retrysettings ServiceProxyFactory をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNonIServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateNonIServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!TServiceInterface CreateNonIServiceProxy&lt;TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.CreateNonIServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="member this.CreateNonIServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface" Usage="serviceProxyFactory.CreateNonIServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface" />
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
            サービスによって実装される TServiceInterface リモート インターフェイスを使用して、指定されたサービスと通信するプロキシを作成します。
            <typeparam name="TServiceInterface">リモート処理は実行されているインターフェイス。サービス インターフェイスは、IService から継承する必要はありません。</typeparam><param name="serviceUri">サービスの Uri</param> 。<param name="partitionKey">サービス パーティションはこのサービス プロキシからの要求の処理を決定する、パーティション キー</param><param name="targetReplicaSelector">どのレプリカまたは、クライアントが接続するサービス パーティションのインスタンスを決定します</param>。<param name="listenerName">サービスに 1 つの通信リスナーがある場合、このパラメーターは省略可能です。サービスのエンドポイントがの形式は {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}。サービスは、複数のエンドポイントを公開するときにこのパラメーターは、リモート通信に使用するには、そのエンドポイントのうちを識別します。</param><returns>リモート処理は実行されているインターフェイスを実装するプロキシ。返されるオブジェクトが実装も<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />インターフェイスです。</returns></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="serviceProxyFactory.CreateServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)</InterfaceMember>
      </Implements>
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
            サービスによって実装される TServiceInterface リモート インターフェイスを使用して、指定されたサービスと通信するプロキシを作成します。
            <typeparam name="TServiceInterface">リモート処理は実行されているインターフェイス</typeparam><param name="serviceUri">サービスの Uri</param> 。<param name="partitionKey">サービス パーティションはこのサービス プロキシからの要求の処理を決定する、パーティション キー</param><param name="targetReplicaSelector">を決定するレプリカまたはサービス パーティションのインスタンス、クライアントが接続する必要があります宛先。</param><param name="listenerName">サービスに 1 つの通信リスナーがある場合、このパラメーターは省略可能です。サービスのエンドポイントがの形式は {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}。サービスは、複数のエンドポイントを公開するときにこのパラメーターは、リモート通信に使用するには、そのエンドポイントのうちを識別します。</param><returns>リモート処理は実行されているインターフェイスを実装するプロキシ。返されるオブジェクトが実装も<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />インターフェイスです。</returns></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>