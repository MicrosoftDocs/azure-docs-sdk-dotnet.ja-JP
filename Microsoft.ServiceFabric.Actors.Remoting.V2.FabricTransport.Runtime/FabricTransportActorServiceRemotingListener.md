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
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />アクター サービス用のアクターとサービスのインターフェイスのリモート処理を提供するファブリック TCP トランスポートを使用します。
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
                アクター サービスの実装です。
            </param>
        <param name="listenerSettings">
                リスナーで使用する設定。
            </param>
        <summary>
                ファブリック TCP ベース トランスポート サービス リモート処理のリスナーを指定されたアクター サービスを構築します。
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
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="messageHandler">
                リモート処理のメッセージを処理するハンドラー。 メッセージは、受信したリスナーに送りますをこのハンドラーにします。
                </param>
        <param name="listenerSettings"></param>
        <param name="serializationProvider"></param>
        <summary>
                ファブリック TCP ベース トランスポート サービス リモート処理のリスナーを指定されたアクター サービスを構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>