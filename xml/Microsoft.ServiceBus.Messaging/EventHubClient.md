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
    <summary><span data-ttu-id="a1e4c-101">Event Hub からイベントを送受信するために使用するアンカー クラスです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-101">An anchor class used to send and receive events to and from an Event Hub.</span></span></summary>
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
        <param name="path"><span data-ttu-id="a1e4c-102">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-102">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="a1e4c-103">新しいインスタンスを作成、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />インスタンス、アプリケーションの構成設定からの接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-103">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> instance, using a connection string from the application configuration settings.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-104">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-104">The newly created Event Hub client object.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-105">このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-105">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="a1e4c-106">ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-106">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="a1e4c-107">セクションの形式は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-107">The format of the section is as follows:</span></span>
            
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
        <param name="endpointAddress"><span data-ttu-id="a1e4c-108">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-108">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="a1e4c-109">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="a1e4c-109">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-110">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-110">The path to the Event Hub.</span></span></param>
        <param name="authContext"><span data-ttu-id="a1e4c-111">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-111">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="a1e4c-112">アサーションの証明書のクライアント資格情報でします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-112">The client assertion certificate credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="a1e4c-113"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-113"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="enableLinkRedirect"><span data-ttu-id="a1e4c-114">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-114">Value indicating whether this transport is ready to be redirected to the server backend.</span></span></param>
        <summary><span data-ttu-id="a1e4c-115">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-115">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-116">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-116">The newly created Event Hub client object.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="a1e4c-117">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-117">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="a1e4c-118">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="a1e4c-118">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-119">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-119">The path to the Event Hub.</span></span></param>
        <param name="authContext"><span data-ttu-id="a1e4c-120">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-120">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="a1e4c-121">アプリの資格情報。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-121">The app credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="a1e4c-122"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-122"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="enableLinkRedirect"><span data-ttu-id="a1e4c-123">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-123">Value indicating whether this transport is ready to be redirected to the server backend.</span></span></param>
        <summary><span data-ttu-id="a1e4c-124">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-124">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-125">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-125">The newly created Event Hub client object.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="a1e4c-126">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-126">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="a1e4c-127">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="a1e4c-127">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-128">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-128">The path to the Event Hub.</span></span></param>
        <param name="authContext"><span data-ttu-id="a1e4c-129">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-129">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="a1e4c-130">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-130">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="a1e4c-131">ユーザーのパスワード資格情報です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-131">The user password credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="a1e4c-132"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-132"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="enableLinkRedirect"><span data-ttu-id="a1e4c-133">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-133">Value indicating whether this transport is ready to be redirected to the server backend.</span></span></param>
        <summary><span data-ttu-id="a1e4c-134">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-134">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-135">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-135">The newly created Event Hub client object.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="a1e4c-136">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-136">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="a1e4c-137">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="a1e4c-137">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-138">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-138">The path to the Event Hub.</span></span></param>
        <param name="authContext"><span data-ttu-id="a1e4c-139">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-139">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="a1e4c-140">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-140">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="a1e4c-141">クライアント アプリで redrectUri です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-141">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="a1e4c-142">プラットフォームのパラメーター</span><span class="sxs-lookup"><span data-stu-id="a1e4c-142">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="a1e4c-143">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="a1e4c-143">User Identifier</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="a1e4c-144"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-144"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="enableLinkRedirect"><span data-ttu-id="a1e4c-145">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-145">Value indicating whether this transport is ready to be redirected to the server backend.</span></span></param>
        <summary><span data-ttu-id="a1e4c-146">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-146">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-147">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-147">The newly created Event Hub client object.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-148">SendBatch または SendBatchAsync 呼び出しの後のイベント データ オブジェクトを追加する場所のバッチを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-148">Creates a batch where event data objects can be added for later SendBatch or SendBatchAsync call.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-149"><see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-149">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />.</span></span></returns>
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
        <param name="connectionString"><span data-ttu-id="a1e4c-150">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-150">The connection string to use.</span></span></param>
        <summary><span data-ttu-id="a1e4c-151">指定された接続文字列を使用して、イベント ハブ クライアントの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-151">Creates a new instance of the Event Hubs client using the specified connection string.</span></span> <span data-ttu-id="a1e4c-152">設定することができます、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />イベント ハブの名前を持つプロパティです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-152">You can populate the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property with the name of the Event Hub.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-153">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-153">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-154">接続を取得するか、Azure ポータルから、またはから作成された、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-154">The connection can be obtained either from the Azure portal, or created from a <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> instance.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="a1e4c-155">パラメーターの connectionString の形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-155">Thrown when the format of the parameter connectionString is incorrect.</span></span></exception>
        <example> <span data-ttu-id="a1e4c-156">ConnectionString で EntityPath を設定する方法を示すサンプル<code>
            var connectionStringBuilder = new ServiceBusConnectionStringBuilder(connectionString);
            connectionStringBuilder.EntityPath = eventHubDescription.Path;</span><span class="sxs-lookup"><span data-stu-id="a1e4c-156">Sample showing how to populate the EntityPath in connectionString <code>
            var connectionStringBuilder = new ServiceBusConnectionStringBuilder(connectionString);
            connectionStringBuilder.EntityPath = eventHubDescription.Path;</span></span>
            
<span data-ttu-id="a1e4c-157">var eventHubClient EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString()); を =</span><span class="sxs-lookup"><span data-stu-id="a1e4c-157">var eventHubClient = EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString());</span></span>
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
        <param name="connectionString"><span data-ttu-id="a1e4c-158">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-158">The connection string to be used.</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-159">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-159">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="a1e4c-160">指定された接続文字列を使用して、イベント ハブ クライアントの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-160">Creates a new instance of the Event Hubs client using the specified connection string.</span></span> <span data-ttu-id="a1e4c-161">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-161">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-162">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-162">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-163">接続を取得するか、Azure ポータルから、またはから作成された、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-163">The connection can be obtained either from the Azure portal, or created from a <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> instance.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="a1e4c-164">パラメーターの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-164">Thrown when the format of the parameters is incorrect.</span></span></exception>
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
        <param name="partitionId"><span data-ttu-id="a1e4c-165">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-165">The ID of the partition.</span></span></param>
        <summary><span data-ttu-id="a1e4c-166">指定されたイベント ハブ パーティションに対して、Event Hubs の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-166">Creates an Event Hubs sender for the specified Event Hubs partition.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-167">返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-167">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> object.</span></span></returns>
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
        <param name="partitionId"><span data-ttu-id="a1e4c-168">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-168">The ID of the partition.</span></span></param>
        <summary><span data-ttu-id="a1e4c-169"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-169">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-170"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-170">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
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
        <param name="publisher"><span data-ttu-id="a1e4c-171">パブリッシャーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-171">The publisher identifier.</span></span></param>
        <summary><span data-ttu-id="a1e4c-172">指定されたパブリッシャに対して、Event Hubs の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-172">Creates an Event Hubs sender for the specified publisher.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-173"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-173">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-174">Event Hubs の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-174">Creates the Event Hubs sender.</span></span> <span data-ttu-id="a1e4c-175">このメソッドは、内部で使用し、ユーザー コードから呼び出すことを意図していません。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-175">This method is for internal use, and not meant to be called from user code.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-176">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-176">The task representing the asynchronous operation.</span></span></returns>
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
        <param name="publisher"><span data-ttu-id="a1e4c-177">パブリッシャーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-177">The publisher identifier.</span></span></param>
        <summary><span data-ttu-id="a1e4c-178"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-178">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-179"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-179">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
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
        <param name="endpointAddress"><span data-ttu-id="a1e4c-180">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-180">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="a1e4c-181">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="a1e4c-181">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="a1e4c-182">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-182">The path to the Event Hub.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="a1e4c-183"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-183"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="enableLinkRedirect"><span data-ttu-id="a1e4c-184">このトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-184">Value indicating whether this transport is ready to be redirected to the server backend.</span></span></param>
        <summary><span data-ttu-id="a1e4c-185">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Azure 管理サービス Id の認証を使用しています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-185">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-186">新しく作成された Event Hub クライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-186">The newly created Event Hub client object.</span></span></returns>
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
            <span data-ttu-id="a1e4c-187">取得またはメモリ内エンティティ レベルのパフォーマンス カウンターを収集するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-187">Gets or sets a value to indicate if entity level perf counters should be collected in memory.</span></span> <span data-ttu-id="a1e4c-188">これのみに影響を与えるエンティティ レベルのカウンター、および名前空間レベルのカウンターは常に収集されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-188">Note that this only affect entity level counters, and namespace level counters are always collected.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="a1e4c-189">これは既定で false に設定 - 既定では意味場合は、このエンティティ レベルのパフォーマンス カウンター収集しないでください。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-189">By default this is set to false - meaning by default we do collect entity level perf counters.</span></span> <span data-ttu-id="a1e4c-190">この値を設定、収集された既存のカウンターは無効にし、収集される新しいエンティティからカウンターを停止するだけです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-190">Setting this value will not affect existing collected counters, and will only stop counters from new entity being collected.</span></span></remarks>
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
        <param name="groupName"><span data-ttu-id="a1e4c-191">グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-191">The name of the group.</span></span></param>
        <summary><span data-ttu-id="a1e4c-192">指定された名前、イベント データの受信操作のコンシューマー グループを返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-192">Returns the consumer group with the specified name, for the receive operation of event data.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-193">A<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />コンシューマー グループに対応するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-193">A <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> instance, corresponding to the consumer group.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-194">イベント データの受信操作の既定のコンシューマー グループを返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-194">Returns the default consumer group, for the receive operation of event data.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-195">既定の <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-195">The default <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-196">既定の ConsumerGroup がチェックポイント操作を実行できません。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-196">Default ConsumerGroup cannot perform checkpoint operations.</span></span> <span data-ttu-id="a1e4c-197">チェックポイント操作を実行するには、ユーザーが明示的な ConsumerGroup を作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-197">To perform checkpoint operations, user should create a explicit ConsumerGroup</span></span></remarks>
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
        <param name="partitionId"><span data-ttu-id="a1e4c-198">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-198">The partition ID.</span></span></param>
        <summary><span data-ttu-id="a1e4c-199">Event Hub の指定したパーティションのランタイム情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-199">Retrieves runtime information for the specified partition of the Event Hub.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-200"><see cref="T:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-200">Returns <see cref="T:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" />.</span></span></returns>
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
        <param name="partitionId"><span data-ttu-id="a1e4c-201">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-201">The partition ID.</span></span></param>
        <summary><span data-ttu-id="a1e4c-202"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-202">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-203"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-203">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-204">Event Hubs のランタイム情報を作成するために必要なを取得<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />または<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-204">Retrieves Event Hubs runtime information, which is required for creating <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> or <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> objects.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-205"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-205">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" />.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-206"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-206">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" />.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-207"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-207">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
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
        <summary><span data-ttu-id="a1e4c-208">中断アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-208">Executes the abort action.</span></span></summary>
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
        <param name="timeout"><span data-ttu-id="a1e4c-209">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-209">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="a1e4c-210">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-210">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="a1e4c-211">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-211">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="a1e4c-212">このオブジェクトは、EndClose に渡されるデリゲート、操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-212">This object is passed to the EndClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="a1e4c-213">開始の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-213">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-214"><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-214">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></returns>
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
        <param name="timeout"><span data-ttu-id="a1e4c-215">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-215">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="a1e4c-216">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-216">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="a1e4c-217">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-217">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="a1e4c-218">このオブジェクトは、EndOpen に渡されるデリゲート、操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-218">This object is passed to the EndOpen delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="a1e4c-219">開始 [開く] アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-219">Executes the begin open action.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-220"><see cref="T:System.IAsyncResult" />非同期の Open 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-220">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Open operation.</span></span></returns>
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
        <param name="timeout"><span data-ttu-id="a1e4c-221">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-221">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="a1e4c-222">閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-222">Executes the close action.</span></span></summary>
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
        <param name="result"><span data-ttu-id="a1e4c-223"><see cref="T:System.IAsyncResult" />非同期の Close 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-223">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></param>
        <summary><span data-ttu-id="a1e4c-224">最後の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-224">Executes the end close action.</span></span></summary>
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
        <param name="result"><span data-ttu-id="a1e4c-225"><see cref="T:System.IAsyncResult" />非同期の Open 操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-225">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Open operation.</span></span></param>
        <summary><span data-ttu-id="a1e4c-226">終了 [開く] アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-226">Executes the end open action.</span></span></summary>
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
        <summary><span data-ttu-id="a1e4c-227">Event Hub のパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-227">Gets the path of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="a1e4c-228">Event Hub のパス。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-228">The path of the Event Hub.</span></span></value>
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
        <summary><span data-ttu-id="a1e4c-229">取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-229">Gets or sets the number of events that any receive operation will actively cache.</span></span> <span data-ttu-id="a1e4c-230">既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ファクトリ メソッドから現在のインスタンスを作成する場合。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-230">By default, this value is inherited from <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> if the current instance is created from the factory method.</span></span> <span data-ttu-id="a1e4c-231">それ以外の場合、既定値は 10,000 です。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-231">Otherwise, the default value is 10,000.</span></span></summary>
        <value><span data-ttu-id="a1e4c-232">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-232">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="a1e4c-233">注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-233">Note that setting the count too low will affect the effective performance of the Event Hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a1e4c-234">値が 10 の必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-234">Thrown if the value is less than the minimum required value of 10.</span></span></exception>
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
        <summary><span data-ttu-id="a1e4c-235">取得または設定の最大サイズ (バイト単位) のいずれかの受信操作の合計がアクティブにキャッシュされます。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-235">Gets or sets the maximum size (in bytes) in total that any receive operation will actively cache.</span></span> <span data-ttu-id="a1e4c-236">各イベント データのサイズによって、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-236">The size of each event data is determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> property.</span></span></summary>
        <value><span data-ttu-id="a1e4c-237"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-237">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks><span data-ttu-id="a1e4c-238">サイズの制限は絶対的な制限ではありませんし、経由で移動できます (PrefetchSizeInBytes/256kBytes) イベントに相当するバイト数と同じくらいです。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-238">The size limit is not an absolute limit, and can go over by as much as (PrefetchSizeInBytes/256kBytes) number of event worth of bytes.</span></span>
            <span data-ttu-id="a1e4c-239">どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />これから作成されたインスタンスは既定ではこの値を継承します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-239">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> created from this instance will inherit this value by default.</span></span> <span data-ttu-id="a1e4c-240">この値に変更内容は、作成済みのコンシューマー グループには反映されませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />変更後に作成します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-240">Changes to this value will not be propagated to already created consumer group, but will be used by new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> created after the change.</span></span> <span data-ttu-id="a1e4c-241">この値に null 以外の値も設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />をゼロにします。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-241">Also setting this value to non-null value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" /> to zero.</span></span>
            <span data-ttu-id="a1e4c-242">低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-242">Note that setting the size too low will affect the effective performance of the Event Hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a1e4c-243">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-243">Thrown when the size value is less than the minimum required value of 260K bytes.</span></span></exception>
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
        <param name="data"><span data-ttu-id="a1e4c-244">イベントのデータ。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-244">The event data.</span></span></param>
        <summary><span data-ttu-id="a1e4c-245">Event Hub にイベント データを送信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-245">Sends event data to an Event Hub.</span></span></summary>
        <remarks><span data-ttu-id="a1e4c-246">どの<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />インスタンス送信がこのメソッドを使用する必要があります、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-246">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> instance send using this method must have the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> set.</span></span></remarks>
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
        <param name="data"><span data-ttu-id="a1e4c-247">送信する <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-247">The <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> to send.</span></span></param>
        <summary><span data-ttu-id="a1e4c-248">Event Hub にイベント データを非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-248">Asynchronously sends event data to an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-249">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-249">The task representing the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-250">どの<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />インスタンス送信がこのメソッドを使用する必要があります、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-250">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> instance send using this method must have the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> set.</span></span></remarks>
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
        <param name="eventDataList"><span data-ttu-id="a1e4c-251">イベント データ インスタンスを含む IEnumerable オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-251">An IEnumerable object containing event data instances.</span></span></param>
        <summary><span data-ttu-id="a1e4c-252">イベント データのバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-252">Sends a batch of event data.</span></span></summary>
        <remarks><span data-ttu-id="a1e4c-253">ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-253">User should make sure the total serialized size of <paramref name="eventDataList" /> should be under the size limit of one event data transmission, which is 256k by default.</span></span> <span data-ttu-id="a1e4c-254">また、バッチを形成するオーバーヘッドがある注意してください。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-254">Also note that there will be some overhead to form the batch.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException"><span data-ttu-id="a1e4c-255">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-255">Thrown if the total serialized size of <paramref name="eventDataList" /> exceeds the allowed size limit for one event transmission (256k by default).</span></span></exception>
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
        <param name="eventDataList"><span data-ttu-id="a1e4c-256">イベント データ インスタンスを含む IEnumerable オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-256">An IEnumerable object containing event data instances.</span></span></param>
        <summary><span data-ttu-id="a1e4c-257">イベント データのバッチを非同期に送信します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-257">Asynchronously sends a batch of event data.</span></span></summary>
        <returns><span data-ttu-id="a1e4c-258"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-258">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks><span data-ttu-id="a1e4c-259">ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-259">User should make sure the total serialized size of <paramref name="eventDataList" /> should be under the size limit of one event data transmission, which is 256k by default.</span></span> <span data-ttu-id="a1e4c-260">また、バッチを形成するオーバーヘッドがある注意してください。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-260">Also note that there will be some overhead to form the batch.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException"><span data-ttu-id="a1e4c-261">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</span><span class="sxs-lookup"><span data-stu-id="a1e4c-261">Thrown if the total serialized size of <paramref name="eventDataList" /> exceeds the allowed size limit for one event transmission (256k by default).</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>