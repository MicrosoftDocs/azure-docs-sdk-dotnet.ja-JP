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
            <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />ファブリック TCP トランスポートを使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />経由でリモート処理は実行されているインターフェイスでアクターと通信する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />です。
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
                サービスからのコールバックを受信するコールバック クライアント。
            </param>
        <summary>
            ファブリック トランスポート ベースのアクターのリモート処理クライアント ファクトリを構築します。
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
                ファブリック トランスポートの設定。 場合は、設定は、セキュリティなしで指定された、または null の既定の設定ではありません。
                </param>
        <param name="callbackClient">
                サービスからのコールバックを受信するコールバック クライアント。
            </param>
        <param name="servicePartitionResolver">
                サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。 既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。
                </param>
        <param name="exceptionHandlers">
                アクターと通信中に発生した例外を処理する例外ハンドラーです。
            </param>
        <param name="traceId">
                このコンポーネントからのトレースを診断で使用する id。
            </param>
        <summary>
            ファブリック トランスポート ベースのアクターのリモート処理クライアント ファクトリを構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>