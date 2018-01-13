<Type Name="CommunicationClientFactoryBase&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public abstract class CommunicationClientFactoryBase&lt;TCommunicationClient&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CommunicationClientFactoryBase`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CommunicationClientFactoryBase(Of TCommunicationClient)&#xA;Implements ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    interface ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt;" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TCommunicationClient">クライアントの通信の種類</typeparam>
    <summary>
            Service fabric サービスと対話する通信のクライアントを作成するためには、ICommunicationClientFactory の基本実装を提供します。 カスタム トランスポートの実装のための通信のクライアントを作成する CommunicationClientFactoryBase クラスを拡張します。 このクラスは、通信のクライアントのキャッシュを保持し、同じサービス エンドポイントへの要求のクライアントを再利用しようとしています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CommunicationClientFactoryBase (Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.#ctor(Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (Optional servicePartitionResolver As IServicePartitionResolver = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional traceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; (servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePartitionResolver">省略可能な ServicePartitionResolver</param>
        <param name="exceptionHandlers">サービスの通信チャネルにクライアントでの例外の省略可能なカスタム例外ハンドラー</param>
        <param name="traceId">このコンポーネントから診断トレースに使用する識別子 </param>
        <summary>
            通信のクライアントのファクトリの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortClient">
      <MemberSignature Language="C#" Value="protected abstract void AbortClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AbortClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.AbortClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AbortClient (client As TCommunicationClient)" />
      <MemberSignature Language="F#" Value="abstract member AbortClient : 'CommunicationClient -&gt; unit" Usage="communicationClientFactoryBase.AbortClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client">クライアントの通信</param>
        <summary>
            指定したクライアントを中止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
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
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
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
    <Member MemberName="CreateClientAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;TCommunicationClient&gt; CreateClientAsync (string endpoint, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; CreateClientAsync(string endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.CreateClientAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateClientAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.CreateClientAsync (endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpoint">レプリカがリッスンしているリスナーのアドレス</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            指定したエンドポイント アドレスの通信のクライアントを作成します。
            </summary>
        <returns>作成された通信のクライアント</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionHandlers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ExceptionHandlers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionHandlers As IEnumerable(Of IExceptionHandler)" />
      <MemberSignature Language="F#" Value="member this.ExceptionHandlers : seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ExceptionHandlers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスの通信チャネルをクライアント上で例外を処理するためには、カスタム例外ハンドラーを取得します。
            </summary>
        <value>例外ハンドラーの一覧</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (previousRsp, targetReplica, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplica" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">以前の ResolvedServicePartition 値</param>
        <param name="targetReplica">レプリカの指定パーティション キーで識別されるパーティションには、クライアントに接続する必要があります</param>
        <param name="listenerName">クライアントが接続する、選択したレプリカのエンドポイントでどのリスナーを指定します。</param>
        <param name="retrySettings">クライアントを作成するときに発生する例外を使用する再試行ポリシーを指定します。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            取得または指定された previousRsp に基づいて解決することによって、指定したリスナー名の CommunicationClient を作成します。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;&#xA;override this.ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="communicationClientFactoryBase.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;ReportOperationExceptionAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="exceptionInformation">サービスと通信するときに発生した例外に関する情報です。</param>
        <param name="retrySettings">報告された例外を処理するために使用する必要があります再試行ポリシーを指定します。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            サービスにメッセージを送信するときに、CommunicationClient で発生する例外を処理します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />オブジェクトを決定する方法この例外の再試行ポリシーです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceResolver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ServiceResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceResolver As IServicePartitionResolver" />
      <MemberSignature Language="F#" Value="member this.ServiceResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス エンドポイントを解決するために、クライアント ファクトリによって使用される ServicePartitionResolver を取得します。
            </summary>
        <value>ServicePartitionResolver</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="protected string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.TraceId" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TraceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このコンポーネントの診断トレース識別子を取得します。
            </summary>
        <value>トレース識別子</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client">通信クライアント</param>
        <summary>
            クライアントがまだ有効な場合に true を返します。 接続指向トランスポートでは、クライアントがサービスに接続していないことを示すために、このメソッドを使用できます。
            </summary>
        <returns>クライアントは、有効な場合は false をそれ以外の場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (string endpoint, TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(string endpoint, !TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (endpoint As String, client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : string * 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient (endpoint, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="endpoint">接続されているクライアントを考えて、予期されるエンドポイントを指定します</param>
        <param name="client">通信クライアント</param>
        <summary>
            クライアントがまだ有効であり、パラメーターで指定されたエンドポイントに接続されている場合に true を返します。
            </summary>
        <returns>クライアントは、有効な場合は false をそれ以外の場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>