<Type Name="IConfidentialClientApplication" FullName="Microsoft.Identity.Client.IConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public interface IConfidentialClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfidentialClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfidentialClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IConfidentialClientApplication = interface&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IClientApplicationBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8c643-101">秘密のクライアント アプリケーションのように Web アプリ/API を使用するコンポーネントです。</span><span class="sxs-lookup"><span data-stu-id="8c643-101">Component to be used for confidential client applications like Web Apps/API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="8c643-102">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="8c643-102">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="scopes"><span data-ttu-id="8c643-103">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-103">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="8c643-104">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8c643-104">Acquires security token from the authority using authorization code previously received.</span></span>
            <span data-ttu-id="8c643-105">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />です。</span><span class="sxs-lookup"><span data-stu-id="8c643-105">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-106">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="8c643-106">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync scopes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="8c643-107">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-107">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="8c643-108">秘密のクライアントのサービスからのトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8c643-108">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="8c643-109">このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。</span><span class="sxs-lookup"><span data-stu-id="8c643-109">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-110">要求されたスコープのアプリケーションのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="8c643-110">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="8c643-111">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-111">Array of scopes requested for resource</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="8c643-112">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、クライアントの資格情報を使用して新しいアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="8c643-112">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using client credentials</span></span></param>
        <summary>
            <span data-ttu-id="8c643-113">秘密のクライアントのサービスからのトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8c643-113">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="8c643-114">このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。</span><span class="sxs-lookup"><span data-stu-id="8c643-114">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-115">要求されたスコープのアプリケーションのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="8c643-115">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="8c643-116">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-116">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="8c643-117">ユーザーを含む UserAssertion のインスタンスのトークン。</span><span class="sxs-lookup"><span data-stu-id="8c643-117">Instance of UserAssertion containing user's token.</span></span></param>
        <summary>
            <span data-ttu-id="8c643-118">取得の代理として-のフローを使用してトークンです。</span><span class="sxs-lookup"><span data-stu-id="8c643-118">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-119">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="8c643-119">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="8c643-120">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-120">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="8c643-121">ユーザーを含む UserAssertion のインスタンスのトークン。</span><span class="sxs-lookup"><span data-stu-id="8c643-121">Instance of UserAssertion containing user's token.</span></span></param>
        <param name="authority"><span data-ttu-id="8c643-122">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="8c643-122">Specific authority for which the token is requested.</span></span> <span data-ttu-id="8c643-123">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="8c643-123">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="8c643-124">取得の代理として-のフローを使用してトークンです。</span><span class="sxs-lookup"><span data-stu-id="8c643-124">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-125">要求されたスコープのユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="8c643-125">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="8c643-126">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-126">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="8c643-127">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="8c643-127">Identifier of the user.</span></span> <span data-ttu-id="8c643-128">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="8c643-128">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="8c643-129">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="8c643-129">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="8c643-130">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="8c643-130">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="8c643-131">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="8c643-131">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-132">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="8c643-132">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
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
        <param name="scopes"><span data-ttu-id="8c643-133">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="8c643-133">Array of scopes requested for resource</span></span></param>
        <param name="redirectUri"><span data-ttu-id="8c643-134">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="8c643-134">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="loginHint"><span data-ttu-id="8c643-135">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="8c643-135">Identifier of the user.</span></span> <span data-ttu-id="8c643-136">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="8c643-136">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="8c643-137">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="8c643-137">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="8c643-138">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="8c643-138">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="8c643-139">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="8c643-139">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="8c643-140">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="8c643-140">Specific authority for which the token is requested.</span></span> <span data-ttu-id="8c643-141">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="8c643-141">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="8c643-142">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="8c643-142">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="8c643-143">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="8c643-143">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>