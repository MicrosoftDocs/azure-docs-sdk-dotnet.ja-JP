<Type Name="IActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory">
  <TypeSignature Language="C#" Value="public interface IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type IActorProxyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アクター プロキシ ファクトリ クラスを作成するメソッドを含むインターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
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
        <returns>IActorProxy および TActorInterface を実装するアクター プロキシ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
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
        <returns>IActorProxy および TActorInterface を実装するアクター プロキシ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
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
        <returns>IServiceProxy および TServiceInterface を実装するサービス プロキシ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
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
        <returns>IServiceProxy および TServiceInterface を実装するサービス プロキシ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>