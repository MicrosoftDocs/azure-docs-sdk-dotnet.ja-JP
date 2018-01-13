<Type Name="TopicClient" FullName="Microsoft.ServiceBus.Messaging.TopicClient">
  <TypeSignature Language="C#" Value="public abstract class TopicClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TopicClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TopicClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type TopicClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>使用されるアンカー クラスにアクセスする、<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />実行時の操作を実行します。</summary>
    <remarks>To be added.</remarks>
    <altmember cref="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
    <example>
      <code>
             MessagingFactorySettings factorySettings MessagingFactory (rutime 操作) の設定を作成する新しい MessagingFactorySettings() = {NetMessagingTransportSettings = 新しい NetMessagingTransportSettings()、資格情報 =TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName、IssuerKey)} です。
             
             MessagingFactory MessagingFactory ファクトリの作成 (myServiceBusNamespace、factorySettings); MessagingFactory.Create を =
                
                /トピックにメッセージを送信する///* * *
             
            トピック クライアント TopicClient myTopicClient を作成するファクトリを = です。CreateTopicClient(myTopic) です。
             
             送信者//MessageSender myMessageSender 作成 myTopicClient.CreateSender(SendMode.Default); を =
             
            メッセージ ボックスの一覧を送信&lt;オブジェクト&gt;問題新しいリストを =&lt;オブジェクト&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="topicClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">メッセージのスケジュール設定に返されます。</param>
        <summary>
            スケジュールされたメッセージを取り消します
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">パス。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> の新しいインスタンスを作成します。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。 ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。 セクションの形式は次のとおりです。
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Sercvice バスの完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">トピックへのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientAssertionCertificate">アサーションの証明書のクライアント資格情報でします。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="transportType">メッセージング トランスポートの種類。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">トピックへのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientCredential">アプリの資格情報。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="transportType">メッセージング トランスポートの種類。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">トピックへのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="userPasswordCredential">ユーザーのパスワード資格情報です。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="transportType">メッセージング トランスポートの種類。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
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
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">トピックへのパス。</param>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="redirectUri">クライアント アプリで redrectUri です。</param>
        <param name="platformParameters">プラットフォームのパラメーター</param>
        <param name="userIdentifier">ユーザーの識別子</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="transportType">メッセージング トランスポートの種類。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />指定された接続文字列を使用します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> を返します。</returns>
        <remarks>このメソッドは、指定された接続文字列がエンティティのパスなどのエンティティ レベルの情報と提供された認証情報が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。</param>
        <param name="path">パス。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />指定した接続文字列とトピックへのパスを使用します。 接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>このメソッドを指定する接続文字列には、エンティティ レベル情報が関連付けられている必要がありますいないために、名前空間レベルの認証を持つ接続文字列でのみ使用する必要があります。</remarks>
        <exception cref="T:System.ArgumentException">パラメーターの形式が正しくない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity (endpointAddress, path, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="path">トピックへのパス。</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</param>
        <param name="transportType">メッセージング トランスポートの種類。</param>
        <summary>新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure 管理サービス Id の認証を使用しています。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (topicPath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">トピックのパスです。</param>
        <summary>ユーティリティ メソッドをトピックのパスとサブスクリプションの名前で指定されたトピックの転送のトピックの配信不能キューを示す完全なパスを形成します。</summary>
        <returns>返します、<see cref="T:System.String" />を表す、指定したトピックの転送のトピックの配信不能キューを示す完全なパスです。 受信側に作成される、または (REST URI) などの URI の構成で、このパスを使用できます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSubQueue">
      <MemberSignature Language="C#" Value="protected bool IsSubQueue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSubQueue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property IsSubQueue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSubQueue : bool" Usage="Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサブキューからメッセージの受信者を作成するかどうかを示す値を設定します。</summary>
        <value>メッセージの受信者がサブキュー; から作成された場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>これを作成するために使用されたメッセージング ファクトリを設定を取得または<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />オブジェクト。</summary>
        <value>これの作成に使用されたメッセージング ファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="topicClient.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginClose (timeout, callback, state)" />
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
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginCreateSender (timeout, callback, state)" />
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
        <param name="state">受信操作に関する情報を格納するユーザー定義のオブジェクト。 このオブジェクトは、<see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" />操作が完了するとします。</param>
        <summary>実行開始操作の送信者を作成します。</summary>
        <returns><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="topicClient.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="topicClient.OnEndClose result" />
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
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="topicClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照します。</param>
        <summary>最後の実行操作の送信者を作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはファイルの完全なパス名を設定します。</summary>
        <value>ファイルの完全なパス名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary> 現在のキュー/トピックから BrokeredMessage をピークします。 </summary>
        <returns> ピーク BrokeredMessage を返します。 Null はピーク操作内でのメッセージを取得できない場合は、戻り<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</returns>
        <remarks>Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"> ピーク開始メッセージのシーケンス番号。 </param>
        <summary> 現在のキュー/トピックから BrokeredMessage をピークします。 </summary>
        <returns> ピーク BrokeredMessage を返します。 Null はピーク操作内でのメッセージを取得できない場合は、戻り<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</returns>
        <remarks>Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"> ここに表示するメッセージの最大数。 </param>
        <summary> 現在のキュー/トピックから BrokeredMessage をピークします。 </summary>
        <returns> ピーク BrokeredMessages の一覧を返します。 ピーク操作内でのメッセージを取得できない場合、空のリストが返される<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</returns>
        <remarks>Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="topicClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message">スケジュールされるメッセージ</param>
        <param name="scheduleEnqueueTimeUtc">エンキューの時刻</param>
        <summary>
            スケジュールされたメッセージを送信します。
            </summary>
        <returns>キャンセルするために必要なシーケンス番号。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="topicClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">送信するメッセージ。</param>
        <summary>使用してメッセージを送信、<see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />です。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:System.ArgumentException">場合にスローされる、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合にスローされます、<paramref name="message" />によって既に送信されて、<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />または<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />既に 1 回です。</exception>
        <exception cref="T:System.OperationCanceledException">クライアントのエンティティを閉じているか、中止された場合にスローされます。</exception>
        <exception cref="T:System.UnauthorizedAccessException">I/O やセキュリティ エラーがある場合にスローされます。</exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException">シリアル化または逆シリアル化中にエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">トピックが存在しない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">メッセージングのエラーがある場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">送信するメッセージ。</param>
        <summary>使用してメッセージを非同期的に送信、<see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />です。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="topicClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">送信するメッセージ。</param>
        <summary>一連の (バッチ処理) の仲介型メッセージを送信します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">送信するメッセージ。</param>
        <summary>(バッチ処理) の仲介型メッセージのセットが非同期的に送信します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>