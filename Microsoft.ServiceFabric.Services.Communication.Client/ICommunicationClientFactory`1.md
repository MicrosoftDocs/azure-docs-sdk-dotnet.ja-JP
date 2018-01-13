<Type Name="ICommunicationClientFactory&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public interface ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationClientFactory`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient">クライアントの通信の種類</typeparam>
    <summary>
            Service fabric サービスと対話する通信のクライアントのファクトリを提供するために実装する必要があります、インターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            通信のクライアントがサービス エンドポイントに接続するときに発生するイベント ハンドラー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            通信のクライアントがサービス エンドポイントから切断するときに発生するイベント ハンドラー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (previousRsp, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
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
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
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
    <Member MemberName="ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync (TCommunicationClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync(!TCommunicationClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="iCommunicationClientFactory.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
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