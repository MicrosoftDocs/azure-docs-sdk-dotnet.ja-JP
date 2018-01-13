<Type Name="ActorProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxy">
  <TypeSignature Language="C#" Value="public abstract class ActorProxy : Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase, Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorProxy extends Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase implements class Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorProxy&#xA;Inherits ProxyBase&#xA;Implements IActorProxy" />
  <TypeSignature Language="F#" Value="type ActorProxy = class&#xA;    inherit ProxyBase&#xA;    interface IActorProxy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            プロキシを実装するアクターのリモート オブジェクトへの基本実装を提供<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />インターフェイスです。
            クライアントのアクターとアクターのアクターの通信に使用されるプロキシ オブジェクトを使用できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ActorProxy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClient As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClient : Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しているインターフェイス。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClientV2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClientV2 As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClientV2 : Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しているインターフェイス。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, Uri serviceUri, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Uri serviceUri, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.Uri,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * Uri * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, serviceUri, listenerName)" />
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
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            リモートのアクター オブジェクトによって実装されるアクター インターフェイスです。 返されるプロキシ オブジェクトでは、このインターフェイスを実装します。
            </typeparam>
        <param name="actorId">プロキシのアクター オブジェクトのアクターの Id です。 このプロキシで呼び出されるメソッドは、この id を持つアクターに送信される要求になります。</param>
        <param name="serviceUri">アクター サービスの Uri。</param>
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
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, applicationName, serviceName, listenerName)" />
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
        <param name="actorId">プロキシ アクター オブジェクトのアクターの ID です。 このプロキシに対してメソッドを呼び出すと、この ID に置き換えます。 アクターに送信される要求</param>
        <param name="applicationName">
            アクター オブジェクトをホストするアクター サービスを含む Service Fabric アプリケーションの名前。
            このパラメーターは、クライアントがその同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることはできます。 詳細については、「解説」を参照してください。 
            </param>
        <param name="serviceName">
            Service Fabric サービスによって構成されたとおりの名前<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクターの実装にします。
            既定では、サービスの名前は、アクター インターフェイスの名前から派生します。 ただし、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />はアクターは、1 つ以上のアクター インターフェイスを実装するか、サービス名が自動的に確認できないので、アクター インターフェイスが別のアクター インターフェイスから派生した場合に必要です。
            </param>
        <param name="listenerName">
            既定では、アクター サービスは、1 つだけリスナーに接続して通信するクライアントを持ちます。
            ただし、複数のリスナーを使用するアクター サービスを構成することはできます。 このパラメーターに接続するリスナーの名前を指定します。
            </param>
        <summary>
            アクター インターフェイスを実装するアクター オブジェクトへのプロキシを作成します。
            </summary>
        <returns>実装するアクター プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />TActorInterface とします。</returns>
        <remarks>
          <para>ApplicationName パラメーターをクライアントが通信するために予定アクター サービスと同じ Service Fabric アプリケーションの一部として実行されている場合は null にすることができます。 アプリケーション名を決定するこの例では、 <see cref="T:System.Fabric.CodePackageActivationContext" />、呼び出すことで取得し、<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />プロパティです。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>