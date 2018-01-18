<Type Name="ConfidentialClientApplication" FullName="Microsoft.Identity.Client.ConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public sealed class ConfidentialClientApplication : Microsoft.Identity.Client.ClientApplicationBase, Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfidentialClientApplication extends Microsoft.Identity.Client.ClientApplicationBase implements class Microsoft.Identity.Client.IClientApplicationBase, class Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfidentialClientApplication&#xA;Inherits ClientApplicationBase&#xA;Implements IConfidentialClientApplication" />
  <TypeSignature Language="F#" Value="type ConfidentialClientApplication = class&#xA;    inherit ClientApplicationBase&#xA;    interface IConfidentialClientApplication&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.ClientApplicationBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IConfidentialClientApplication</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="aac0e-101">秘密のクライアント アプリケーションのように Web アプリ/API を使用するクラスです。</span><span class="sxs-lookup"><span data-stu-id="aac0e-101">Class to be used for confidential client applications like Web Apps/API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="aac0e-102">アプリケーションのクライアント Id。</span><span class="sxs-lookup"><span data-stu-id="aac0e-102">Client Id of the application.</span></span> <span data-ttu-id="aac0e-103">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-103">REQUIRED.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="aac0e-104">アプリケーションのリダイレクト URI。</span><span class="sxs-lookup"><span data-stu-id="aac0e-104">Redirect URI of the application.</span></span> <span data-ttu-id="aac0e-105">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-105">REQUIRED.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="aac0e-106">アプリケーションのクライアント資格情報です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-106">Client credential for the application.</span></span> <span data-ttu-id="aac0e-107">証明書またはシークレットがあります。</span><span class="sxs-lookup"><span data-stu-id="aac0e-107">Could be a certificate or a secret.</span></span> <span data-ttu-id="aac0e-108">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-108">REQUIRED.</span></span></param>
        <param name="userTokenCache"><span data-ttu-id="aac0e-109">ユーザー トークンを保存するためのトークン キャッシュします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-109">Token cache for saving user tokens.</span></span> <span data-ttu-id="aac0e-110">OPTIONAL. (省略可能。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-110">OPTIONAL.</span></span></param>
        <param name="appTokenCache"><span data-ttu-id="aac0e-111">アプリケーション/クライアント トークンを保存するためのトークン キャッシュします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-111">Token cache for saving application/client tokens.</span></span> <span data-ttu-id="aac0e-112">OPTIONAL. (省略可能。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-112">OPTIONAL.</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-113">クラスのインスタンスを作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="aac0e-113">Constructor to create instance of the class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string authority, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, authority, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="aac0e-114">アプリケーションのクライアント Id。</span><span class="sxs-lookup"><span data-stu-id="aac0e-114">Client Id of the application.</span></span> <span data-ttu-id="aac0e-115">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-115">REQUIRED.</span></span></param>
        <param name="authority"><span data-ttu-id="aac0e-116">クライアント アプリケーションに使用する機関です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-116">Authority to be used for the client application.</span></span> <span data-ttu-id="aac0e-117">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-117">REQUIRED.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="aac0e-118">アプリケーションのリダイレクト URI。</span><span class="sxs-lookup"><span data-stu-id="aac0e-118">Redirect URI of the application.</span></span> <span data-ttu-id="aac0e-119">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-119">REQUIRED.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="aac0e-120">アプリケーションのクライアント資格情報です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-120">Client credential for the application.</span></span> <span data-ttu-id="aac0e-121">証明書またはシークレットがあります。</span><span class="sxs-lookup"><span data-stu-id="aac0e-121">Could be a certificate or a secret.</span></span> <span data-ttu-id="aac0e-122">REQUIRED. (必須。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-122">REQUIRED.</span></span></param>
        <param name="userTokenCache"><span data-ttu-id="aac0e-123">ユーザー トークンを保存するためのトークン キャッシュします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-123">Token cache for saving user tokens.</span></span> <span data-ttu-id="aac0e-124">OPTIONAL. (省略可能。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-124">OPTIONAL.</span></span></param>
        <param name="appTokenCache"><span data-ttu-id="aac0e-125">アプリケーション/クライアント トークンを保存するためのトークン キャッシュします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-125">Token cache for saving application/client tokens.</span></span> <span data-ttu-id="aac0e-126">OPTIONAL. (省略可能。)</span><span class="sxs-lookup"><span data-stu-id="aac0e-126">OPTIONAL.</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-127">クラスのインスタンスを作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="aac0e-127">Constructor to create instance of the class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="aac0e-128">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="aac0e-128">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="scopes"><span data-ttu-id="aac0e-129">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-129">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-130">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="aac0e-130">Acquires security token from the authority using authorization code previously received.</span></span>
            <span data-ttu-id="aac0e-131">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-131">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-132">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="aac0e-132">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync scopes" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-133">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-133">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-134">秘密のクライアントのサービスからのトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="aac0e-134">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="aac0e-135">このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-135">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-136">要求されたスコープのアプリケーションのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="aac0e-136">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-137">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-137">Array of scopes requested for resource</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="aac0e-138">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、クライアントの資格情報を使用して新しいアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="aac0e-138">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using client credentials</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-139">秘密のクライアントのサービスからのトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="aac0e-139">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="aac0e-140">このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。</span><span class="sxs-lookup"><span data-stu-id="aac0e-140">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-141">要求されたスコープのアプリケーションのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="aac0e-141">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-142">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-142">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="aac0e-143">ユーザーを含む UserAssertion のインスタンスのトークン。</span><span class="sxs-lookup"><span data-stu-id="aac0e-143">Instance of UserAssertion containing user's token.</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-144">取得の代理として-のフローを使用してトークンです。</span><span class="sxs-lookup"><span data-stu-id="aac0e-144">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-145">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="aac0e-145">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-146">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-146">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="aac0e-147">ユーザーを含む UserAssertion のインスタンスのトークン。</span><span class="sxs-lookup"><span data-stu-id="aac0e-147">Instance of UserAssertion containing user's token.</span></span></param>
        <param name="authority"><span data-ttu-id="aac0e-148">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-148">Specific authority for which the token is requested.</span></span> <span data-ttu-id="aac0e-149">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="aac0e-149">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-150">取得の代理として-のフローを使用してトークンです。</span><span class="sxs-lookup"><span data-stu-id="aac0e-150">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-151">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="aac0e-151">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-152">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-152">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="aac0e-153">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-153">Identifier of the user.</span></span> <span data-ttu-id="aac0e-154">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-154">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="aac0e-155">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="aac0e-155">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="aac0e-156">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="aac0e-156">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-157">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="aac0e-157">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-158">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-158">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="aac0e-159">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="aac0e-159">Array of scopes requested for resource</span></span></param>
        <param name="redirectUri"><span data-ttu-id="aac0e-160">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="aac0e-160">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="loginHint"><span data-ttu-id="aac0e-161">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-161">Identifier of the user.</span></span> <span data-ttu-id="aac0e-162">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-162">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="aac0e-163">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="aac0e-163">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="aac0e-164">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="aac0e-164">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="aac0e-165">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-165">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="aac0e-166">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-166">Specific authority for which the token is requested.</span></span> <span data-ttu-id="aac0e-167">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="aac0e-167">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="aac0e-168">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="aac0e-168">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="aac0e-169">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="aac0e-169">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>