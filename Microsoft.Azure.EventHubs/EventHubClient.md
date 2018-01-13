<Type Name="EventHubClient" FullName="Microsoft.Azure.EventHubs.EventHubClient">
  <TypeSignature Language="C#" Value="public abstract class EventHubClient : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EventHubClient extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EventHubClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubClient = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスのすべて EventHub クライアント操作ここから開始を固定します。
            「<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />」を参照してください。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override sealed System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;CloseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            閉じに関連付けられているリソースを解放<see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />です。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.Azure.EventHubs.ITokenProvider,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.Azure.EventHubs.ITokenProvider * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, tokenProvider, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.EventHubs.ITokenProvider" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">イベント ハブのパス</param>
        <param name="tokenProvider">認証のセキュリティ トークンを生成するトークン プロバイダー。</param>
        <param name="operationTimeout">Event Hubs の操作の操作がタイムアウトします。</param>
        <param name="transportType">接続のトランスポートの種類。</param>
        <summary>
            イベント ハブを指定されたエンドポイント、エンティティのパス、およびトークン プロバイダーを使用してクライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">イベント ハブのパス</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientAssertionCertificate">アサーションの証明書のクライアント資格情報でします。</param>
        <param name="operationTimeout">Event Hubs の操作の操作がタイムアウトします。</param>
        <param name="transportType">接続のトランスポートの種類。</param>
        <summary>
            指定されたエンドポイント、エンティティのパス、AAD 認証コンテキストを使用して Event Hub クライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">イベント ハブのパス</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientCredential">アプリの資格情報。</param>
        <param name="operationTimeout">Event Hubs の操作の操作がタイムアウトします。</param>
        <param name="transportType">接続のトランスポートの種類。</param>
        <summary>
            指定されたエンドポイント、エンティティのパス、AAD 認証コンテキストを使用して Event Hub クライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">イベント ハブのパス</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="redirectUri">クライアント アプリケーションで redirectUri です。</param>
        <param name="platformParameters">プラットフォームのパラメーター</param>
        <param name="userIdentifier">ユーザーの識別子</param>
        <param name="operationTimeout">Event Hubs の操作の操作がタイムアウトします。</param>
        <param name="transportType">接続のトランスポートの種類。</param>
        <summary>
            指定されたエンドポイント、エンティティのパス、AAD 認証コンテキストを使用して Event Hub クライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.Azure.EventHubs.EventDataBatch" Usage="eventHubClient.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>イベント データ オブジェクトを追加する場所のバッチを作成後の SendAsync 呼び出しです。</summary>
        <returns><see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, DateTime startTime, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.DateTime,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * DateTime * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startTime">日付時刻インスタント受信操作が開始イベントを受け取るからです。 受信したイベントである<see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />この時点より後です。</param>
        <param name="epoch">一意識別子 (エポック値) パーティション/リースの所有権を強制するのには、サービスが使用されます。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>
            ベース エポックの作成 EventHub の受信側でパーティション id とパーティションのストリームの先頭からの受信開始を指定します。
            受信側では、特定のコンシューマー グループから特定の EventHub パーティションが作成されます。
            <para />ベース エポック レシーバーを作成するとき、次に注意することが重要: <para />-所有権実施: ベース エポック レシーバーを作成するとすべてされるまで非エポック受信側が同じ consumerGroup パーティション コンボを作成することはできませんレシーバーをコンボ ボックスが閉じられます。
            <para />所有権を盗む: consumerGroup パーティション コンボ エポック値が高いと受信側が作成される場合、古いエポック レシーバーそのコンボが強制的に閉じられたをされます。
            <para />-その受信者からすべての操作、期日の consumerGroup パーティション コンボに所有権の紛失に閉じられたすべての受信者は ReceiverDisconnectedException を取得します。
            </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startingOffset">イベントの受信を開始するオフセット。 ストリームの使用の開始位置から受信するには<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="epoch">パーティション/リースの所有権を強制するのには、サービスが使用する一意な識別子 (エポック値)。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>
            ベース エポックの作成 EventHub の受信側でパーティション id とパーティションのストリームの先頭からの受信開始を指定します。
            受信側では、特定のコンシューマー グループから特定の EventHub パーティションが作成されます。
            <para />ベース エポック レシーバーを作成するとき、次に注意することが重要: <para />-所有権実施: ベース エポック レシーバーを作成するとすべてされるまで非エポック受信側が同じ consumerGroup パーティション コンボを作成することはできませんレシーバーをコンボ ボックスが閉じられます。
            <para />所有権を盗む: consumerGroup パーティション コンボ エポック値が高いと受信側が作成される場合、古いエポック レシーバーそのコンボが強制的に閉じられたをされます。
            <para />-その受信者からすべての操作、期日の consumerGroup パーティション コンボに所有権の紛失に閉じられたすべての受信者は ReceiverDisconnectedException を取得します。
            </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Boolean,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * bool * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startingOffset">イベントの受信を開始するオフセット。 ストリームの使用の開始位置から受信するには<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="offsetInclusive">startingOffset true に設定するが、包括的なオフセット - として扱われます返される最初のイベントの意味があるは、開始オフセット。 返される通常の最初のイベントは、開始オフセットの後のイベントです。</param>
        <param name="epoch">パーティション/リースの所有権を強制するのには、サービスが使用する一意な識別子 (エポック値)。 </param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>
             ベース エポックの作成 EventHub の受信側でパーティション id とパーティションのストリームの先頭からの受信開始を指定します。
             受信側では、特定のコンシューマー グループから特定の EventHub パーティションが作成されます。
             <para />ベース エポック レシーバーを作成するとき、次に注意することが重要: <para />-所有権実施: ベース エポック レシーバーを作成するとすべてされるまで非エポック受信側が同じ consumerGroup パーティション コンボを作成することはできませんレシーバーをコンボ ボックスが閉じられます。
             <para />所有権を盗む: consumerGroup パーティション コンボ エポック値が高いと受信側が作成される場合、古いエポック レシーバーそのコンボが強制的に閉じられたをされます。
             <para />-その受信者からすべての操作、期日の consumerGroup パーティション コンボに所有権の紛失に閉じられたすべての受信者は ReceiverDisconnectedException を取得します。
             </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"></param>
        <summary>
            指定された接続文字列を使用して、イベント ハブ クライアントの新しいインスタンスを作成します。 Event Hub の名前を持つ EntityPath プロパティを設定することができます。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionSender">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreatePartitionSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionSender (partitionId As String) As PartitionSender" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionSender : string -&gt; Microsoft.Azure.EventHubs.PartitionSender" Usage="eventHubClient.CreatePartitionSender partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">送信する EventHub の partitionId、<see cref="T:Microsoft.Azure.EventHubs.EventData" />にします。</param>
        <summary>
            作成、<see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />を発行できます<see cref="T:Microsoft.Azure.EventHubs.EventData" />の特定の EventHub パーティション (送信者の種類 iii に直接。 一覧の下)。
            <para />3 つのパターン/EventHubs に送信する方法があります: <para>i.<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>ii です。 <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>iii です。<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para></summary>
        <returns>作成された PartitionSender</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionSender" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, DateTime startTime, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.DateTime,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * DateTime * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startTime, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startTime">受信操作インスタントは開始日時からのイベントが表示されます。 受信したイベントである<see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />この時点より後です。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>
            EventHub レシーバーを作成すると、パーティション id と指定したオフセットからの受信開始を指定します。
            受信側では、特定のコンシューマー グループから特定の EventHub パーティションが作成されます。
            </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startingOffset, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startingOffset, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startingOffset">イベントの受信を開始するオフセット。 ストリームの使用の開始位置から受信するには<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>
            特定のコンシューマー グループから特定の EventHub パーティションのレシーバーを作成します。
            <para />注: ありますパーティションごとの ConsumerGroup あたりの並列で実行できるレシーバーの最大数。 Event Hub サービスによって制限が適用されます - 現在の制限は並列で 5 つの受信者です。 複数の受信者を持つが、同じコンシューマー グループで離れ/コンボをパーティション分割されるオフセットからの読み取りは大幅なパフォーマンスの影響があります。 
            </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,System.Boolean,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * bool * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">この受信者は、グループ化する必要がありますコンシューマー グループの名前。</param>
        <param name="partitionId">パーティションに属している、受信者 Id です。 受信したすべてのデータは、このパーティションのみからなります。</param>
        <param name="startOffset">イベントの受信を開始するオフセット。 ストリームの使用の開始から受信します。<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="offsetInclusive">つまり、最初のイベントが返される場合は、startingOffset true に設定するが、包括的なオフセット - として扱われます、<param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
            1 つを持つ開始オフセット。 返される通常の最初のイベントは、開始オフセットの後のイベントです。</param>
        <param name="receiverOptions">To be added.</param>
        <summary>
            EventHub レシーバーを作成すると、パーティション id と指定したオフセットからの受信開始を指定します。
            受信側では、特定のコンシューマー グループから特定の EventHub パーティションが作成されます。
            </summary>
        <returns>作成された PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity (Uri endpointAddress, string entityPath, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string entityPath, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity (endpointAddress, entityPath, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">イベント ハブのパス</param>
        <param name="operationTimeout">Event Hubs の操作の操作がタイムアウトします。</param>
        <param name="transportType">接続のトランスポートの種類。</param>
        <summary>
            Azure 管理サービス Id の認証を指定されたエンドポイントをエンティティのパスを使用して、イベント ハブ クライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。 </summary>
        <value> クライアントがアクセスする場合は true。<see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" />を使用して<see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />です。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string" Usage="Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            EventHub の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.GetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetPartitionRuntimeInformationAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティションの id。</param>
        <summary>Event Hub の指定したパーティションのランタイム情報を取得します。</summary>
        <returns><see cref="T:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetRuntimeInformationAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            EventHub のランタイム情報を取得します
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCloseAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnCloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.OnCloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Nullable&lt;DateTime&gt; startTime, Nullable&lt;long&gt; epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int64&gt; epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCreateReceiver(System.String,System.String,System.String,System.Boolean,System.Nullable{System.DateTime},System.Nullable{System.Int64},Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateReceiver : string * string * string * bool * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.OnCreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="epoch" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"></param>
        <param name="partitionId"></param>
        <param name="startOffset"></param>
        <param name="offsetInclusive"></param>
        <param name="startTime"></param>
        <param name="epoch"></param>
        <param name="receiverOptions"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.OnGetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.OnGetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRetryPolicyUpdate">
      <MemberSignature Language="C#" Value="protected override void OnRetryPolicyUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnRetryPolicyUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnRetryPolicyUpdate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnRetryPolicyUpdate ()" />
      <MemberSignature Language="F#" Value="override this.OnRetryPolicyUpdate : unit -&gt; unit" Usage="eventHubClient.OnRetryPolicyUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            再試行ポリシーの更新は、ここを処理します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><see cref="T:Microsoft.Azure.EventHubs.EventData" />送出します。</param>
        <summary>
            送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />EventHub にします。 送信済みの EventData が任意に選択された EventHubs パーティションに入ります。
            <para>(およびその sendBatch オーバー ロード) メソッドとして公開されている各 EventHubs に送信する 3 つの方法がある:</para><para>i.<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>ii です。  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>iii です。 <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para>このメソッドを使用して送信する場合: <para>)、<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />操作を高可用性にする必要がありますと</para><para>b)、データ間に均等に分散する必要がありますすべてのパーティションです。例外である、パーティションのサブセットを使用できる場合</para><see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />送信、 <see cref="T:Microsoft.Azure.EventHubs.EventData" /> EventHub のパーティションのいずれかに EventData を転送するさらに、サービス ゲートウェイにします。
            アルゴリズムの転送、メッセージを次に示します:<para>しました。すべてのパーティション間でデータを均等に分散して、EventHub パーティション EventDatas を転送 (ex: ラウンド ロビン EventHub のすべてのパーティションに EventDatas) </para> <para>ii です。EventHub パーティションの 1 つは少しの間、サービス ゲートウェイの検出されるようには自動的に作成し、メッセージ送信操作を高可用性にする - 別の利用可能なパーティションを転送します。</para></summary>
        <returns>ときに完了するタスクを送信操作が行われます。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventDatas" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDatas">EventHub へ送信するイベントのバッチ</param>
        <summary>
            バッチが送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />EventHub にします。 送信済みの EventData が任意に選択された EventHub パーティションに入ります。
            これは、EventHub に送信する最も推奨される方法です。
            
            <para>オーバー ロードを参照してください EventHubs、この特定の種類の送信の理解に送信する 3 つの方法がある<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />、1 つの送信に使用される<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。バッチを送信する必要がある場合は、このオーバー ロードを使用して<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</para>
            
            バッチを送信する<see cref="T:Microsoft.Azure.EventHubs.EventData" />の次の場合に役に立ちます: <para>i。  効率的な送信 - のバッチ送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />最適に EventHub のサービスに作成されたセッションの数を使用して全体的なスループットを最大化します</para>。<para>ii です。 複数の送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />のトランザクションにします。Acheieve ACID プロパティでは、ゲートウェイ サービスがすべて転送<see cref="T:Microsoft.Azure.EventHubs.EventData" />'s 単一 EventHub へのバッチでパーティションに分割します。</para></summary>
        <returns>ときに完了するタスクを送信操作が行われます。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <example>
            サンプル コード: 
            <code>
            var client = EventHubClient.Create("__connectionString__");
            while (true)
            {
                var events = new List&lt;EventData&gt;();
                for (int count = 1; count &lt; 11; count++)
                {
                    var payload = new PayloadEvent(count);
                    byte[] payloadBytes = Encoding.UTF8.GetBytes(JsonConvert.SerializeObject(payload));
                    var sendEvent = new EventData(payloadBytes);
                    var applicationProperties = new Dictionary&lt;string, string&gt;();
                    applicationProperties["from"] = "csharpClient";
                    sendEvent.Properties = applicationProperties;
                    events.Add(sendEvent);
                }
                    
                await client.SendAsync(events);
                Console.WriteLine("Sent Batch... Size: {0}", events.Count);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventData, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventData"><see cref="T:Microsoft.Azure.EventHubs.EventData" />送出します。</param>
        <param name="partitionKey">partitionKey に EventData を送信する partitionId を決定に対してハッシュ化されます。 このサービスで受信したメッセージにアクセスできます<see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />です。</param>
        <summary>
             送信、'<see cref="T:Microsoft.Azure.EventHubs.EventData" /> EventHub への partitionKey とします。 すべて<see cref="T:Microsoft.Azure.EventHubs.EventData" />の同じパーティションに契約を獲得する保証は、partitionKey とします。
             この送信パターンは、一般的な可用性と待機時間経過に伴うデータの相関関係を強調します。
             <para>(およびそのバッチのオーバー ロード) メソッドとして公開されている各 EventHubs に送信する 3 つの方法がある:</para><para>i.<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>ii です。 <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>iii です。<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para>場合は、この種類の送信を使用:<para>な) 送信者のインスタンスに基づいたイベントの関連付けの必要性があります。送信者が UniqueId を生成し、受信メッセージの相関関係の使用可能な - partitionKey として設定できます</para><para>b)、クライアントは複数のパーティションのデータの分布を制御しようとしています。</para>
             複数 PartitionKeys は、1 つのパーティションにマップする可能性があります。 EventHubs サービスは、PartitionKey をパーティション Id にマップするのに、独自のハッシュ アルゴリズムを使用します。
             この種類の送信 (特定の partitionKey を使用して送信する) を使用する可能性がありますもに均等に分散されていないパーティション。 
             </summary>
        <returns>送信操作が完了したときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData), partitionKey As String) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventDatas, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;SendAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventDatas">EventHub へ送信するイベントのバッチ</param>
        <param name="partitionKey">partitionKey に EventData を送信する partitionId を決定に対してハッシュ化されます。 このサービスで受信したメッセージにアクセスできます<see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />です。</param>
        <summary>
            送信、' のバッチ<see cref="T:Microsoft.Azure.EventHubs.EventData" />同じ partitionKey で ' EventHub にします。 すべて<see cref="T:Microsoft.Azure.EventHubs.EventData" />の同じパーティションに契約を獲得する保証は、partitionKey とします。
            複数の PartitionKey は、1 つのパーティションにマップされます。
            <para>オーバー ロードを参照してください EventHubs、この特定の種類の送信の理解に送信する 3 つの方法がある<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />は、同じ種類の送信と 1 つの送信に使用する<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</para>バッチを送信する<see cref="T:Microsoft.Azure.EventHubs.EventData" />の次の場合に役に立ちます: <para>i。  効率的な送信 - のバッチ送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />EventHubs サービスに作成されたセッションの数を最適に使用して、全体的なスループットを最大化します</para>。<para>ii です。 1 つのトランザクションで複数のイベントを送信しています。これは、理由、バッチ内のすべてのイベントが送信される理由 (できるようにする 1 つのパーティションのみに送信する) 同じ partitionKey する必要があります。</para></summary>
        <returns>送信操作が完了したときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>