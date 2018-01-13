<Type Name="ActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory">
  <TypeSignature Language="C#" Value="public class ActorProxyFactory : Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorProxyFactory&#xA;Implements IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type ActorProxyFactory = class&#xA;    interface IActorProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            リモートのアクターのオブジェクトへのプロキシを作成するファクトリ クラスを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">リモート処理の通信のクライアントのファクトリを作成するファクトリ メソッド。</param>
        <param name="retrySettings">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />クラス V1 リモート処理クライアント ファクトリを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">リモート処理の通信のクライアントのファクトリを作成するファクトリ メソッド。</param>
        <param name="retrySettings">プロキシによってリモート オブジェクトへの呼び出しの設定を再試行してください。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />クラス V2 リモート処理クライアントのファクトリを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。 返されるプロキシ オブジェクトでは、このインターフェイスを実装します。
            </typeparam>
        <param name="serviceUri">アクター サービスの Uri。</param>
        <param name="actorId">プロキシのアクター オブジェクトのアクターの Id です。 このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</param>
        <param name="listenerName">
            既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。
            複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。
            </param>
        <summary>
            アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。
            </summary>
        <returns>実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。 返されるプロキシ オブジェクトでは、このインターフェイスを実装します。
            </typeparam>
        <param name="actorId">プロキシのアクター オブジェクトのアクターの Id です。 このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</param>
        <param name="applicationName">
            アクター オブジェクトをホストするアクター サービスを含む Service Fabric アプリケーションの名前です。
            このパラメーターは、クライアントがその同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることはできます。 詳細については、「解説」を参照してください。 
            </param>
        <param name="serviceName">
            Service Fabric サービスによって構成されたとおりの名前<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクターの実装にします。
            既定では、サービスの名前は、アクター インターフェイスの名前から派生します。 ただし<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />はアクターが 1 つ以上にアクター インターフェイスを実装するか、serviceName の決定は自動的に加えられることはできません、アクター インターフェイスが別のアクター インターフェイスから派生した場合に必要です。
            </param>
        <param name="listenerName">
            既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。
            複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。
            </param>
        <summary>
            アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。
            </summary>
        <returns>実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">アクター サービスによって実装されるサービスのインターフェイスです。</typeparam>
        <param name="serviceUri">接続するアクター サービスの Uri。</param>
        <param name="actorId">アクターの id です。 作成されたプロキシは、この id を持つアクターをホストするアクター サービスのパーティションに接続されます。</param>
        <param name="listenerName">
            既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。
            複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。
            </param>
        <summary>
            指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">アクター サービスによって実装されるサービスのインターフェイスです。</typeparam>
        <param name="serviceUri">接続するアクター サービスの Uri。</param>
        <param name="partitionKey">接続するアクター サービス パーティションのキー。</param>
        <param name="listenerName">
            既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。
            複数のリスナーをアクター サービスを構成することは、listenerName パラメーターへの接続にリスナーの名前を指定します。
            </param>
        <summary>
            指定したアクターの id をホストしているおよび指定した種類のサービス インターフェイスを実装しているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>