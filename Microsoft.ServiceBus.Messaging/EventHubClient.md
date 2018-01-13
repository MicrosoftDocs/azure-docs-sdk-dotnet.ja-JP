<Type Name="EventHubClient" FullName="Microsoft.ServiceBus.Messaging.EventHubClient">
  <TypeSignature Language="C#" Value="public abstract class EventHubClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EventHubClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EventHubClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubClient = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Event Hub からイベントを送受信するために使用するアンカー クラスです。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>新しいインスタンスを作成、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />インスタンス、アプリケーションの構成設定からの接続文字列を使用します。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。 ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。 セクションの形式は次のとおりです。
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">Event Hub へのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientAssertionCertificate">アサーションの証明書のクライアント資格情報でします。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="enableLinkRedirect">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientCredential, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">Event Hub へのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientCredential">アプリの資格情報。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="enableLinkRedirect">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">Event Hub へのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="userPasswordCredential">ユーザーのパスワード資格情報です。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="enableLinkRedirect">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">Event Hub へのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="redirectUri">クライアント アプリで redrectUri です。</param>
        <param name="platformParameters">プラットフォームのパラメーター</param>
        <param name="userIdentifier">ユーザーの識別子</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="enableLinkRedirect">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="eventHubClient.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>SendBatch または SendBatchAsync 呼び出しの後のイベント データ オブジェクトを追加する場所のバッチを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。</param>
        <summary>指定された接続文字列を使用して、イベント ハブ クライアントの新しいインスタンスを作成します。 設定することができます、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />イベント ハブの名前を持つプロパティです。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</returns>
        <remarks>接続を取得するか、Azure ポータルから、またはから作成された、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />インスタンス。</remarks>
        <exception cref="T:System.ArgumentException">パラメーターの connectionString の形式が正しくない場合にスローされます。</exception>
        <example> ConnectionString で EntityPath を設定する方法を示すサンプル<code>
            var connectionStringBuilder = new ServiceBusConnectionStringBuilder(connectionString);
            connectionStringBuilder.EntityPath = eventHubDescription.Path;
            
            var eventHubClient EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString()); を =
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。</param>
        <param name="path">Event Hub へのパス。</param>
        <summary>指定された接続文字列を使用して、イベント ハブ クライアントの新しいインスタンスを作成します。 接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</returns>
        <remarks>接続を取得するか、Azure ポータルから、またはから作成された、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />インスタンス。</remarks>
        <exception cref="T:System.ArgumentException">パラメーターの形式が正しくない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionedSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubSender CreatePartitionedSender (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubSender CreatePartitionedSender(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionedSender (partitionId As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionedSender : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="eventHubClient.CreatePartitionedSender partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティションの ID。</param>
        <summary>指定されたイベント ハブ パーティションに対して、Event Hubs の送信者を作成します。</summary>
        <returns>返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionedSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreatePartitionedSenderAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreatePartitionedSenderAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionedSenderAsync (partitionId As String) As Task(Of EventHubSender)" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionedSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;" Usage="eventHubClient.CreatePartitionedSenderAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティションの ID。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubSender CreateSender (string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubSender CreateSender(string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSender (publisher As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="member this.CreateSender : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="eventHubClient.CreateSender publisher" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">パブリッシャーの識別子です。</param>
        <summary>指定されたパブリッシャに対して、Event Hubs の送信者を作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSenderAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateSenderAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateSenderAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSenderAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateSenderAsync () As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="abstract member CreateSenderAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="eventHubClient.CreateSenderAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Event Hubs の送信者を作成します。 このメソッドは、内部で使用し、ユーザー コードから呼び出すことを意図していません。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreateSenderAsync (string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreateSenderAsync(string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSenderAsync (publisher As String) As Task(Of EventHubSender)" />
      <MemberSignature Language="F#" Value="member this.CreateSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;" Usage="eventHubClient.CreateSenderAsync publisher" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">パブリッシャーの識別子です。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWithManagedServiceIdentity (endpointAddress As Uri, path As String, Optional operationTimeout As Nullable(Of TimeSpan) = null, Optional enableLinkRedirect As Boolean = true) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateWithManagedServiceIdentity (endpointAddress, path, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">Event Hub へのパス。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="enableLinkRedirect">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure 管理サービス Id の認証を使用しています。</summary>
        <returns>新しく作成された Event Hub クライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableEntityLevelPerformanceCounters">
      <MemberSignature Language="C#" Value="public bool DisableEntityLevelPerformanceCounters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableEntityLevelPerformanceCounters As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableEntityLevelPerformanceCounters : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.DisableEntityLevelPerformanceCounters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメモリ内エンティティ レベルのパフォーマンス カウンターを収集するかどうかを示す値を設定します。 これのみに影響を与えるエンティティ レベルのカウンター、および名前空間レベルのカウンターは常に収集されることに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>これは既定で false に設定 - 既定では意味場合は、このエンティティ レベルのパフォーマンス カウンター収集しないでください。 この値を設定、収集された既存のカウンターは無効にし、収集される新しいエンティティからカウンターを停止するだけです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetConsumerGroup (string groupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetConsumerGroup(string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetConsumerGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroup (groupName As String) As EventHubConsumerGroup" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroup : string -&gt; Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" Usage="eventHubClient.GetConsumerGroup groupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName">グループの名前。</param>
        <summary>指定された名前、イベント データの受信操作のコンシューマー グループを返します。</summary>
        <returns>A<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />コンシューマー グループに対応するインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefaultConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetDefaultConsumerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetDefaultConsumerGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetDefaultConsumerGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDefaultConsumerGroup () As EventHubConsumerGroup" />
      <MemberSignature Language="F#" Value="member this.GetDefaultConsumerGroup : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" Usage="eventHubClient.GetDefaultConsumerGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>イベント データの受信操作の既定のコンシューマー グループを返します。</summary>
        <returns>既定の <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />。</returns>
        <remarks>既定の ConsumerGroup がチェックポイント操作を実行できません。 チェックポイント操作を実行するには、ユーザーが明示的な ConsumerGroup を作成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation GetPartitionRuntimeInformation (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation GetPartitionRuntimeInformation(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionRuntimeInformation (partitionId As String) As PartitionRuntimeInformation" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionRuntimeInformation : string -&gt; Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&#xA;override this.GetPartitionRuntimeInformation : string -&gt; Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" Usage="eventHubClient.GetPartitionRuntimeInformation partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティションの id。</param>
        <summary>Event Hub の指定したパーティションのランタイム情報を取得します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of PartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;&#xA;override this.GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;" Usage="eventHubClient.GetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティションの id。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation GetRuntimeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation GetRuntimeInformation() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRuntimeInformation () As EventHubRuntimeInformation" />
      <MemberSignature Language="F#" Value="abstract member GetRuntimeInformation : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&#xA;override this.GetRuntimeInformation : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" Usage="eventHubClient.GetRuntimeInformation " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Event Hubs のランタイム情報を作成するために必要なを取得<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />または<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />オブジェクト。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;&#xA;override this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;" Usage="eventHubClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubClient.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>中断アクションを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubClient.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">受信操作に関する情報を格納するユーザー定義のオブジェクト。 このオブジェクトは、EndClose に渡されるデリゲート、操作が完了するとします。</param>
        <summary>開始の閉じる操作を実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubClient.OnBeginOpen (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">受信操作に関する情報を格納するユーザー定義のオブジェクト。 このオブジェクトは、EndOpen に渡されるデリゲート、操作が完了するとします。</param>
        <summary>開始 [開く] アクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期の Open 操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubClient.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <summary>閉じる操作を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubClient.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</param>
        <summary>最後の閉じる操作を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubClient.OnEndOpen result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />非同期の Open 操作を参照します。</param>
        <summary>終了 [開く] アクションを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub のパスを取得します。</summary>
        <value>Event Hub のパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。 既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ファクトリ メソッドから現在のインスタンスを作成する場合。 それ以外の場合、既定値は 10,000 です。</summary>
        <value>メッセージの受信者が同時に要求メッセージの数。</value>
        <remarks> 注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 10 の必要な最小値より小さい場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定の最大サイズ (バイト単位) のいずれかの受信操作の合計がアクティブにキャッシュされます。 各イベント データのサイズによって、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />プロパティです。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>サイズの制限は絶対的な制限ではありませんし、経由で移動できます (PrefetchSizeInBytes/256kBytes) イベントに相当するバイト数と同じくらいです。
            どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />これから作成されたインスタンスは既定ではこの値を継承します。 この値に変更内容は、作成済みのコンシューマー グループには反映されませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />変更後に作成します。 この値に null 以外の値も設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />をゼロにします。
            低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Send(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Send(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (data As EventData)" />
      <MemberSignature Language="F#" Value="member this.Send : Microsoft.ServiceBus.Messaging.EventData -&gt; unit" Usage="eventHubClient.Send data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">イベントのデータ。</param>
        <summary>Event Hub にイベント データを送信します。</summary>
        <remarks>どの<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />インスタンス送信がこのメソッドを使用する必要があります、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />を設定します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendAsync(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (data As EventData) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">送信する <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />。</param>
        <summary>Event Hub にイベント データを非同期的に送信します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>どの<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />インスタンス送信がこのメソッドを使用する必要があります、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />を設定します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (eventDataList As IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; unit" Usage="eventHubClient.SendBatch eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">イベント データ インスタンスを含む IEnumerable オブジェクト。</param>
        <summary>イベント データのバッチを送信します。</summary>
        <remarks>ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。 また、バッチを形成するオーバーヘッドがある注意してください。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (eventDataList As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendBatchAsync eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">イベント データ インスタンスを含む IEnumerable オブジェクト。</param>
        <summary>イベント データのバッチを非同期に送信します。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。 また、バッチを形成するオーバーヘッドがある注意してください。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</exception>
      </Docs>
    </Member>
  </Members>
</Type>