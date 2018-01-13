<Type Name="ActorServiceProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceProxy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceProxy" />
  <TypeSignature Language="F#" Value="type ActorServiceProxy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Service Fabric クラスターで実行しているアクター サービスとの対話し、アクター サービス レベルの操作を実行するクライアントで使用されるプロキシを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri">接続するアクター サービスの URI。</param>
        <param name="actorId">アクターの ID です。 作成されたプロキシはこの ID に置き換えます。 アクターをホストするアクター サービスのパーティションに接続します。</param>
        <param name="listenerName">
            アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。
            ただし、複数のリスナーを使用するアクター サービスを構成することはできます。 このパラメーターに接続するリスナーの名前を指定します。
            </param>
        <summary>
            指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />と<see cref="T:Microsoft.ServiceFabric.Actors.IActorService" />インターフェイスです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, long partitionKey, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As IActorService" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri">接続するアクター サービスの URI。</param>
        <param name="partitionKey">接続するアクター サービス パーティションのキー。</param>
        <param name="listenerName">
            アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。
            ただし、複数のリスナーを使用するアクター サービスを構成することはできます。 このパラメーターに接続するリスナーの名前を指定します。
            </param>
        <summary>
            指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />と<see cref="T:Microsoft.ServiceFabric.Actors.IActorService" />インターフェイスです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
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
        <param name="serviceUri">接続するアクター サービスの URI。</param>
        <param name="actorId">アクターの ID です。 作成されたプロキシはこの ID に置き換えます。 アクターをホストするアクター サービスのパーティションに接続します。</param>
        <param name="listenerName">
            アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。
            ただし、複数のリスナーを使用するアクター サービスを構成することはできます。 このパラメーターに接続するリスナーの名前を指定します。
            </param>
        <summary>
            指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
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
        <param name="serviceUri">接続するアクター サービスの URI。</param>
        <param name="partitionKey">接続するアクター サービス パーティションのキー。</param>
        <param name="listenerName">
            アクター サービスの既定値は 1 つだけリスナーに接続して通信するクライアントです。
            ただし、複数のリスナーを使用するアクター サービスを構成することはできます。 このパラメーターに接続するリスナーの名前を指定します。
            </param>
        <summary>
            指定した型のアクターと指定した型のサービス インターフェイスを実装するをホストしているアクター サービスへのプロキシを作成します。
            </summary>
        <returns>実装するサービス プロキシ オブジェクト<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />TServiceInterface とします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>