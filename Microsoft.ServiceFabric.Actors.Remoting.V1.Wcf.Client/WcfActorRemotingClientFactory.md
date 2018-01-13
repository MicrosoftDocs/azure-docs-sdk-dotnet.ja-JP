<Type Name="WcfActorRemotingClientFactory" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class WcfActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfActorRemotingClientFactory extends Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfActorRemotingClientFactory&#xA;Inherits WcfServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type WcfActorRemotingClientFactory = class&#xA;    inherit WcfServiceRemotingClientFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> Windows Communication Foundation を使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />アクター サービスと関係者によって、ホスト経由でリモート処理は、アクターとサービスのインターフェイスを使用して通信するために<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" />です。
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (callbackClient As IServiceRemotingCallbackClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory callbackClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                アクター リモート処理のファクトリを WCF 構成要素に基づいています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingClientFactory (System.ServiceModel.Channels.Binding clientBinding, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory.#ctor(System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientBinding As Binding, callbackClient As IServiceRemotingCallbackClient, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory : System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory (clientBinding, callbackClient, exceptionHandlers, servicePartitionResolver, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                クライアントに使用する WCF バインドします。 使用して、バインディングの既定のクライアントを作成するクライアントのバインディングが null の場合<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
                </param>
        <param name="callbackClient">
                サービスからのコールバックを受信するコールバック クライアント。
            </param>
        <param name="exceptionHandlers">
                サービスと通信中に発生した例外を処理する例外ハンドラーです。
            </param>
        <param name="servicePartitionResolver">
                サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。 既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。
                </param>
        <param name="traceId">
                このコンポーネントからのトレースを診断で使用する id。
            </param>
        <summary>
                アクター リモート処理のファクトリを WCF 構成要素に基づいています。
            </summary>
        <remarks>
                このファクトリを使用して<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />と<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />、だけでなく、コンス トラクターに指定された例外ハンドラーです。 
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>