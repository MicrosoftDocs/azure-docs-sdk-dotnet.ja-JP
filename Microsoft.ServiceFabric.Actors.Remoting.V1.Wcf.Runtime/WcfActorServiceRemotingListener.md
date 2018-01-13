<Type Name="WcfActorServiceRemotingListener" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfActorServiceRemotingListener extends Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfActorServiceRemotingListener&#xA;Inherits WcfServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfActorServiceRemotingListener = class&#xA;    inherit WcfServiceRemotingListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />アクター サービスのインターフェイスのリモート処理を提供する Windows Communication Foundation を使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, System.ServiceModel.Channels.Binding listenerBinding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class System.ServiceModel.Channels.Binding listenerBinding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService * System.ServiceModel.Channels.Binding -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener (actorService, listenerBinding)" />
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
        <param name="actorService">アクター サービスです。</param>
        <param name="listenerBinding">リスナーに対して使用する WCF バインドします。 場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
            </param>
        <summary>
            アクター リモート処理のリスナーを WCF 構成要素に基づいています。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener (serviceContext, serviceRemotingMessageHandler, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceRemotingMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="serviceRemotingMessageHandler">リモート処理のメッセージの受信と処理ハンドラー。 メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。
            </param>
        <param name="listenerBinding">リスナーに対して使用する WCF バインドします。 場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。
            </param>
        <param name="address">WCF のリスナーを使用するエンドポイント アドレス。 指定しない場合、"ServiceEndpoint"サービス マニフェストで定義されているをという名前の既定のエンドポイント リソースを使用して、エンドポイント アドレスが作成された指定されているか null です。 
            </param>
        <summary>
            サービスのリモート処理のリスナーを WCF 構成要素に基づいています。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>