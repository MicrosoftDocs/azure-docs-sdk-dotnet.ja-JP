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
    <summary><span data-ttu-id="2d7e8-101">使用されるアンカー クラスにアクセスする、<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />実行時の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-101">An anchor class used to access a <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> to perform run-time operations.</span></span></summary>
    <remarks>To be added.</remarks>
    <altmember cref="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
    <example>
      <code>
             <span data-ttu-id="2d7e8-102">MessagingFactorySettings factorySettings MessagingFactory (rutime 操作) の設定を作成する新しい MessagingFactorySettings() = {NetMessagingTransportSettings = 新しい NetMessagingTransportSettings()、資格情報 =TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName、IssuerKey)} です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-102">// Create settings for the MessagingFactory (for rutime operations) MessagingFactorySettings factorySettings = new MessagingFactorySettings() { NetMessagingTransportSettings = new NetMessagingTransportSettings(), Credential = TransportClientCredentialBase.CreateSharedSecretCredential(IssuerName, IssuerKey), };</span></span>
             
             <span data-ttu-id="2d7e8-103">MessagingFactory MessagingFactory ファクトリの作成 (myServiceBusNamespace、factorySettings); MessagingFactory.Create を =</span><span class="sxs-lookup"><span data-stu-id="2d7e8-103">// Create the MessagingFactory MessagingFactory factory = MessagingFactory.Create(myServiceBusNamespace, factorySettings);</span></span>
                
                <span data-ttu-id="2d7e8-104">/トピックにメッセージを送信する///\* \* \*</span><span class="sxs-lookup"><span data-stu-id="2d7e8-104">//******************************************************************************** //                          Sending messages to a Topic //********************************************************************************</span></span>
             
            <span data-ttu-id="2d7e8-105">トピック クライアント TopicClient myTopicClient を作成するファクトリを = です。CreateTopicClient(myTopic) です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-105">// Create topic client TopicClient myTopicClient = factory.CreateTopicClient(myTopic);</span></span>
             
             <span data-ttu-id="2d7e8-106">送信者//MessageSender myMessageSender 作成 myTopicClient.CreateSender(SendMode.Default); を =</span><span class="sxs-lookup"><span data-stu-id="2d7e8-106">// Create a sender //MessageSender myMessageSender = myTopicClient.CreateSender(SendMode.Default);</span></span>
             
            <span data-ttu-id="2d7e8-107">メッセージ ボックスの一覧を送信&lt;オブジェクト&gt;問題新しいリストを =&lt;オブジェクト&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="2d7e8-107">// Send messages List &lt;object&gt; Issues = new List &lt;object&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
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
        <param name="sequenceNumber"><span data-ttu-id="2d7e8-108">メッセージのスケジュール設定に返されます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-108">Returned on scheduling a message.</span></span></param>
        <summary>
            <span data-ttu-id="2d7e8-109">スケジュールされたメッセージを取り消します</span><span class="sxs-lookup"><span data-stu-id="2d7e8-109">Cancels a scheduled message</span></span>
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
        <param name="path"><span data-ttu-id="2d7e8-110">パス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-110">The path.</span></span></param>
        <summary><span data-ttu-id="2d7e8-111"><see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> の新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-111">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-112">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-112">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-113">このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-113">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="2d7e8-114">ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-114">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="2d7e8-115">セクションの形式は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-115">The format of the section is as follows:</span></span>
            
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
        <param name="endpointAddress"><span data-ttu-id="2d7e8-116">Sercvice バスの完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-116">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="2d7e8-117">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2d7e8-117">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-118">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-118">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="2d7e8-119">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-119">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="2d7e8-120">アサーションの証明書のクライアント資格情報でします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-120">The client assertion certificate credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="2d7e8-121"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-121"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="2d7e8-122">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-122">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="2d7e8-123">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-123">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-124">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-124">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="2d7e8-125">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-125">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="2d7e8-126">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2d7e8-126">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-127">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-127">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="2d7e8-128">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-128">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="2d7e8-129">アプリの資格情報。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-129">The app credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="2d7e8-130"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-130"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="2d7e8-131">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-131">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="2d7e8-132">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-132">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-133">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-133">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="2d7e8-134">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-134">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="2d7e8-135">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2d7e8-135">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-136">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-136">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="2d7e8-137">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-137">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="2d7e8-138">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-138">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="2d7e8-139">ユーザーのパスワード資格情報です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-139">The user password credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="2d7e8-140"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-140"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="2d7e8-141">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-141">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="2d7e8-142">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-142">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-143">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-143">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="2d7e8-144">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-144">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="2d7e8-145">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2d7e8-145">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-146">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-146">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="2d7e8-147">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-147">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="2d7e8-148">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-148">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="2d7e8-149">クライアント アプリで redrectUri です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-149">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="2d7e8-150">プラットフォームのパラメーター</span><span class="sxs-lookup"><span data-stu-id="2d7e8-150">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="2d7e8-151">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="2d7e8-151">User Identifier</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="2d7e8-152"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-152"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="2d7e8-153">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-153">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="2d7e8-154">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-154">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-155">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-155">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
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
        <param name="connectionString"><span data-ttu-id="2d7e8-156">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-156">The connection string to use.</span></span></param>
        <summary><span data-ttu-id="2d7e8-157">新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />指定された接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-157">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-158"><see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-158">Returns <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-159">このメソッドは、指定された接続文字列がエンティティのパスなどのエンティティ レベルの情報と提供された認証情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-159">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
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
        <param name="connectionString"><span data-ttu-id="2d7e8-160">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-160">The connection string to use.</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-161">パス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-161">The path.</span></span></param>
        <summary><span data-ttu-id="2d7e8-162">新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />指定した接続文字列とトピックへのパスを使用します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-162">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> using the specified connection string and path to the topic.</span></span> <span data-ttu-id="2d7e8-163">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-163">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-164">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-164">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-165">このメソッドを指定する接続文字列には、エンティティ レベル情報が関連付けられている必要がありますいないために、名前空間レベルの認証を持つ接続文字列でのみ使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-165">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="2d7e8-166">パラメーターの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-166">Thrown when the format of the parameters is incorrect.</span></span></exception>
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
        <param name="endpointAddress"><span data-ttu-id="2d7e8-167">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-167">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="2d7e8-168">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2d7e8-168">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="2d7e8-169">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-169">The path to the topic.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="2d7e8-170"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-170"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="2d7e8-171">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-171">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="2d7e8-172">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Azure 管理サービス Id の認証を使用しています。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-172">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-173">作成された <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-173">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
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
        <param name="topicPath"><span data-ttu-id="2d7e8-174">トピックのパスです。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-174">The topic path.</span></span></param>
        <summary><span data-ttu-id="2d7e8-175">ユーティリティ メソッドをトピックのパスとサブスクリプションの名前で指定されたトピックの転送のトピックの配信不能キューを示す完全なパスを形成します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-175">A utility method that, given the topic path and subscription name, forms a full path that points to the dead letter queue of the topic's transfer topic.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-176">返します、<see cref="T:System.String" />を表す、指定したトピックの転送のトピックの配信不能キューを示す完全なパスです。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-176">Returns a <see cref="T:System.String" /> representing a full path that points to the dead letter queue of the transfer topic of the specified topic.</span></span> <span data-ttu-id="2d7e8-177">受信側に作成される、または (REST URI) などの URI の構成で、このパスを使用できます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-177">This path can be used in receiver creation or in URI formation (such as a REST URI).</span></span></returns>
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
        <summary><span data-ttu-id="2d7e8-178">取得またはサブキューからメッセージの受信者を作成するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-178">Gets or sets a value that indicates whether the message receiver is created from a subqueue.</span></span></summary>
        <value><span data-ttu-id="2d7e8-179">メッセージの受信者がサブキュー; から作成された場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-179">true if the message receiver is created from a subqueue; otherwise, false.</span></span></value>
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
        <summary><span data-ttu-id="2d7e8-180">これを作成するために使用されたメッセージング ファクトリを設定を取得または<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-180">Gets or sets the messaging factory that was used in creating this <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> object.</span></span></summary>
        <value><span data-ttu-id="2d7e8-181">これの作成に使用されたメッセージング ファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-181">The messaging factory that was used in creating this <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> object.</span></span></value>
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
        <summary><span data-ttu-id="2d7e8-182">中断アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-182">Executes the abort action.</span></span></summary>
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
        <param name="timeout"><span data-ttu-id="2d7e8-183">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-183">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="2d7e8-184">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-184">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="2d7e8-185">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-185">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="2d7e8-186">このオブジェクトは、EndClose に渡されるデリゲート、操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-186">This object is passed to the EndClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="2d7e8-187">開始の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-187">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-188"><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-188">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></returns>
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
        <param name="timeout"><span data-ttu-id="2d7e8-189">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-189">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="2d7e8-190">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-190">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="2d7e8-191">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-191">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="2d7e8-192">このオブジェクトは、<see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" />操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-192">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" /> when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="2d7e8-193">実行開始操作の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-193">Executes the begin create sender action.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-194"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-194">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></returns>
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
        <param name="timeout"><span data-ttu-id="2d7e8-195">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-195">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="2d7e8-196">閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-196">Executes the close action.</span></span></summary>
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
        <param name="result"><span data-ttu-id="2d7e8-197"><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-197">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></param>
        <summary><span data-ttu-id="2d7e8-198">最後の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-198">Executes the end close action.</span></span></summary>
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
        <param name="result"><span data-ttu-id="2d7e8-199"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-199">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="2d7e8-200">最後の実行操作の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-200">Executes the end create sender action.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-201">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-201">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
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
        <summary><span data-ttu-id="2d7e8-202">取得またはファイルの完全なパス名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-202">Gets or sets the full pathname of the file.</span></span></summary>
        <value><span data-ttu-id="2d7e8-203">ファイルの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-203">The full pathname of the file.</span></span></value>
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
        <summary> <span data-ttu-id="2d7e8-204">現在のキュー/トピックから BrokeredMessage をピークします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-204">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="2d7e8-205">ピーク BrokeredMessage を返します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-205">return the peeked BrokeredMessage.</span></span> <span data-ttu-id="2d7e8-206">Null はピーク操作内でのメッセージを取得できない場合は、戻り<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-206">A null is return if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-207">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-207">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
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
        <param name="fromSequenceNumber"> <span data-ttu-id="2d7e8-208">ピーク開始メッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-208">The sequence number of message to start peeking from.</span></span> </param>
        <summary> <span data-ttu-id="2d7e8-209">現在のキュー/トピックから BrokeredMessage をピークします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-209">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="2d7e8-210">ピーク BrokeredMessage を返します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-210">return the peeked BrokeredMessage.</span></span> <span data-ttu-id="2d7e8-211">Null はピーク操作内でのメッセージを取得できない場合は、戻り<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-211">A null is return if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-212">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-212">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
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
        <param name="messageCount"> <span data-ttu-id="2d7e8-213">ここに表示するメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-213">The maximum number of messages to peek.</span></span> </param>
        <summary> <span data-ttu-id="2d7e8-214">現在のキュー/トピックから BrokeredMessage をピークします。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-214">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="2d7e8-215">ピーク BrokeredMessages の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-215">return a list of peeked BrokeredMessages.</span></span> <span data-ttu-id="2d7e8-216">ピーク操作内でのメッセージを取得できない場合、空のリストが返される<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-216">An empty list is returned if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="2d7e8-217">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-217">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
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
        <param name="message"><span data-ttu-id="2d7e8-218">スケジュールされるメッセージ</span><span class="sxs-lookup"><span data-stu-id="2d7e8-218">Message to be scheduled</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="2d7e8-219">エンキューの時刻</span><span class="sxs-lookup"><span data-stu-id="2d7e8-219">Time of enqueue</span></span></param>
        <summary>
            <span data-ttu-id="2d7e8-220">スケジュールされたメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-220">Sends a scheduled message</span></span>
            </summary>
        <returns><span data-ttu-id="2d7e8-221">キャンセルするために必要なシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-221">Sequence number that is needed for cancelling.</span></span></returns>
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
        <param name="message"><span data-ttu-id="2d7e8-222">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-222">The message to send.</span></span></param>
        <summary><span data-ttu-id="2d7e8-223">使用してメッセージを送信、<see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-223">Sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="2d7e8-224">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-224">Thrown when operation times out. Timeout period is initialized through the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="2d7e8-225">場合にスローされる、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が null です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-225">Thrown when the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2d7e8-226">場合にスローされます、<paramref name="message" />によって既に送信されて、<see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />または<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />既に 1 回です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-226">Thrown if the <paramref name="message" /> has already been sent by a <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> or <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> once already.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="2d7e8-227">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-227">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="2d7e8-228">I/O やセキュリティ エラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-228">Thrown if there is an I/O or security error.</span></span></exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException"><span data-ttu-id="2d7e8-229">シリアル化または逆シリアル化中にエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-229">Thrown when an error occurs during serialization or deserialization.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="2d7e8-230">トピックが存在しない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-230">Thrown if the topic does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="2d7e8-231">メッセージングのエラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-231">Thrown if there is a messaging error.</span></span></exception>
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
        <param name="message"><span data-ttu-id="2d7e8-232">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-232">The message to send.</span></span></param>
        <summary><span data-ttu-id="2d7e8-233">使用してメッセージを非同期的に送信、<see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />です。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-233">Asynchronously sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span></span></summary>
        <returns><span data-ttu-id="2d7e8-234">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-234">The asynchronous result of the operation.</span></span></returns>
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
        <param name="messages"><span data-ttu-id="2d7e8-235">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-235">The messages to send.</span></span></param>
        <summary><span data-ttu-id="2d7e8-236">一連の (バッチ処理) の仲介型メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-236">Sends a set of brokered messages (for batch processing).</span></span></summary>
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
        <param name="messages"><span data-ttu-id="2d7e8-237">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-237">The messages to send.</span></span></param>
        <summary><span data-ttu-id="2d7e8-238">(バッチ処理) の仲介型メッセージのセットが非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-238">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="2d7e8-239">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="2d7e8-239">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>