<Type Name="WcfServiceRemotingClientFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingClientFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingClientFactory&#xA;Implements ICommunicationClientFactory(Of IServiceRemotingClient), IServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingClientFactory = class&#xA;    interface IServiceRemotingClientFactory&#xA;    interface ICommunicationClientFactory&lt;IServiceRemotingClient&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> Windows Communication Foundation を使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient" />WcfServiceRemotingListener 経由でリモート処理は実行されているインターフェイス経由でステートレスおよびステートフルなサービスと通信するには
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingClientFactory (System.ServiceModel.Channels.Binding clientBinding = null, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null, Func&lt;System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,string,Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract&gt;&gt; createWcfClientFactory = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackClient, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId, class System.Func`6&lt;class System.ServiceModel.Channels.Binding, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver, string, class Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract, class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract&gt;&gt; createWcfClientFactory, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.#ctor(System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,System.Func{System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory{Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract}},Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientBinding As Binding = null, Optional callbackClient As IServiceRemotingCallbackMessageHandler = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null, Optional createWcfClientFactory As Func(Of Binding, IEnumerable(Of IExceptionHandler), IServicePartitionResolver, String, IServiceRemotingCallbackContract, WcfCommunicationClientFactory(Of IServiceRemotingContract)) = null, Optional serializationProvider As IServiceRemotingMessageSerializationProvider = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory : System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string * Func&lt;System.ServiceModel.Channels.Binding, seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver, string, Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract, Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract&gt;&gt; * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory (clientBinding, callbackClient, exceptionHandlers, servicePartitionResolver, traceId, createWcfClientFactory, serializationProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
        <Parameter Name="createWcfClientFactory" Type="System.Func&lt;System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract&gt;&gt;" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                クライアントに使用する WCF バインドします。 クライアントのバインディングが指定されていないか、null、既定のクライアントのバインドを作成を使用して場合<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
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
        <param name="createWcfClientFactory">
                デリゲートを作成する関数<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />を使用して、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract" />です。
                </param>
        <param name="serializationProvider"></param>
        <summary>
                サービスのリモート処理クライアントのファクトリを WCF 構成要素に基づいています。
            </summary>
        <remarks>
                このファクトリを使用して<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />と<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />だけでなく、コンス トラクターに指定された例外ハンドラーです。 
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントがサービス エンドポイントに接続されているときに発生するイベント ハンドラー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントがサービス エンドポイントから切断されているときに発生するイベント ハンドラー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemotingMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.GetRemotingMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemotingMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory&#xA;override this.GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="wcfServiceRemotingClientFactory.GetRemotingMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory.GetRemotingMessageBodyFactory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            要求と応答のリモート処理のメッセージ本文を作成するために使用メッセージ ファクトリを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V2#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V2-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">以前の ResolvedServicePartition 値</param>
        <param name="targetReplicaSelector">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</param>
        <param name="listenerName">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</param>
        <param name="retrySettings">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを再解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。 
            
            フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V2#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V2-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">サービスの Uri を解決するのには</param>
        <param name="partitionKey">解決するのには、パーティションを識別するキー</param>
        <param name="targetReplicaSelector">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</param>
        <param name="listenerName">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</param>
        <param name="retrySettings">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            1 つまたは複数の通信リスナーを含む指定されたサービスのパーティションを解決し、指定された listenerName に対応するエンドポイントと通信するクライアントを返します。 
            
            フォームのサービスのエンドポイントは、{「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) オブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.ReportOperationExceptionAsync (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V2#Client#IServiceRemotingClient&gt;#ReportOperationExceptionAsync(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClient" />
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">クライアントの通信</param>
        <param name="exceptionInformation">サービスと通信中に発生した例外に関する情報。</param>
        <param name="retrySettings">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />再試行ポリシーでこの例外の情報を提供するオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>