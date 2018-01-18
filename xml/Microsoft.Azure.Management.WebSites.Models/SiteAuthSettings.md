<Type Name="SiteAuthSettings" FullName="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings">
  <TypeSignature Language="C#" Value="public class SiteAuthSettings : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteAuthSettings extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteAuthSettings&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteAuthSettings = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a8d2e-101">Azure アプリのサービス認証の構成設定/承認の機能です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-101">Configuration settings for the Azure App Service Authentication / Authorization feature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-102">SiteAuthSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-102">Initializes a new instance of the SiteAuthSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettings (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; enabled = null, string runtimeVersion = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction = null, Nullable&lt;bool&gt; tokenStoreEnabled = null, System.Collections.Generic.IList&lt;string&gt; allowedExternalRedirectUrls = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; defaultProvider = null, Nullable&lt;double&gt; tokenRefreshExtensionHours = null, string clientId = null, string clientSecret = null, string issuer = null, System.Collections.Generic.IList&lt;string&gt; allowedAudiences = null, System.Collections.Generic.IList&lt;string&gt; additionalLoginParams = null, string googleClientId = null, string googleClientSecret = null, System.Collections.Generic.IList&lt;string&gt; googleOAuthScopes = null, string facebookAppId = null, string facebookAppSecret = null, System.Collections.Generic.IList&lt;string&gt; facebookOAuthScopes = null, string twitterConsumerKey = null, string twitterConsumerSecret = null, string microsoftAccountClientId = null, string microsoftAccountClientSecret = null, System.Collections.Generic.IList&lt;string&gt; microsoftAccountOAuthScopes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; enabled, string runtimeVersion, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction, valuetype System.Nullable`1&lt;bool&gt; tokenStoreEnabled, class System.Collections.Generic.IList`1&lt;string&gt; allowedExternalRedirectUrls, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; defaultProvider, valuetype System.Nullable`1&lt;float64&gt; tokenRefreshExtensionHours, string clientId, string clientSecret, string issuer, class System.Collections.Generic.IList`1&lt;string&gt; allowedAudiences, class System.Collections.Generic.IList`1&lt;string&gt; additionalLoginParams, string googleClientId, string googleClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; googleOAuthScopes, string facebookAppId, string facebookAppSecret, class System.Collections.Generic.IList`1&lt;string&gt; facebookOAuthScopes, string twitterConsumerKey, string twitterConsumerSecret, string microsoftAccountClientId, string microsoftAccountClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; microsoftAccountOAuthScopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider},System.Nullable{System.Double},System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional enabled As Nullable(Of Boolean) = null, Optional runtimeVersion As String = null, Optional unauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction) = null, Optional tokenStoreEnabled As Nullable(Of Boolean) = null, Optional allowedExternalRedirectUrls As IList(Of String) = null, Optional defaultProvider As Nullable(Of BuiltInAuthenticationProvider) = null, Optional tokenRefreshExtensionHours As Nullable(Of Double) = null, Optional clientId As String = null, Optional clientSecret As String = null, Optional issuer As String = null, Optional allowedAudiences As IList(Of String) = null, Optional additionalLoginParams As IList(Of String) = null, Optional googleClientId As String = null, Optional googleClientSecret As String = null, Optional googleOAuthScopes As IList(Of String) = null, Optional facebookAppId As String = null, Optional facebookAppSecret As String = null, Optional facebookOAuthScopes As IList(Of String) = null, Optional twitterConsumerKey As String = null, Optional twitterConsumerSecret As String = null, Optional microsoftAccountClientId As String = null, Optional microsoftAccountClientSecret As String = null, Optional microsoftAccountOAuthScopes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings : string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; * Nullable&lt;double&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings (id, name, kind, type, enabled, runtimeVersion, unauthenticatedClientAction, tokenStoreEnabled, allowedExternalRedirectUrls, defaultProvider, tokenRefreshExtensionHours, clientId, clientSecret, issuer, allowedAudiences, additionalLoginParams, googleClientId, googleClientSecret, googleOAuthScopes, facebookAppId, facebookAppSecret, facebookOAuthScopes, twitterConsumerKey, twitterConsumerSecret, microsoftAccountClientId, microsoftAccountClientSecret, microsoftAccountOAuthScopes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="unauthenticatedClientAction" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt;" />
        <Parameter Name="tokenStoreEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="allowedExternalRedirectUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="defaultProvider" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt;" />
        <Parameter Name="tokenRefreshExtensionHours" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="allowedAudiences" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="additionalLoginParams" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="googleClientId" Type="System.String" />
        <Parameter Name="googleClientSecret" Type="System.String" />
        <Parameter Name="googleOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="facebookAppId" Type="System.String" />
        <Parameter Name="facebookAppSecret" Type="System.String" />
        <Parameter Name="facebookOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="twitterConsumerKey" Type="System.String" />
        <Parameter Name="twitterConsumerSecret" Type="System.String" />
        <Parameter Name="microsoftAccountClientId" Type="System.String" />
        <Parameter Name="microsoftAccountClientSecret" Type="System.String" />
        <Parameter Name="microsoftAccountOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a8d2e-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="a8d2e-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="a8d2e-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="a8d2e-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-106">Resource type.</span></span></param>
        <param name="enabled"><span data-ttu-id="a8d2e-107">&lt;コード&gt;true&lt;/code&gt;場合、認証/承認の機能は現在のアプリに対応している、それ以外の&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-107">&lt;code&gt;true&lt;/code&gt; if the Authentication / Authorization feature is enabled for the current app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="a8d2e-108">認証の RuntimeVersion/承認機能の現在のアプリケーション用に使用します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-108">The RuntimeVersion of the Authentication / Authorization feature in use for the current app.</span></span>
            <span data-ttu-id="a8d2e-109">この値の設定は、認証に特定の機能の動作を制御できます/承認モジュール。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-109">The setting in this value can control the behavior of certain features in the Authentication / Authorization module.</span></span></param>
        <param name="unauthenticatedClientAction"><span data-ttu-id="a8d2e-110">認証されていないクライアントが、アプリにアクセスしようとしたときに実行するアクション。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-110">The action to take when an unauthenticated client attempts to access the app.</span></span> <span data-ttu-id="a8d2e-111">使用可能な値が含まれます: 'RedirectToLoginPage'、'AllowAnonymous'</span><span class="sxs-lookup"><span data-stu-id="a8d2e-111">Possible values include: 'RedirectToLoginPage', 'AllowAnonymous'</span></span></param>
        <param name="tokenStoreEnabled"><span data-ttu-id="a8d2e-112">&lt;コード&gt;true&lt;/code&gt;ログイン フロー中に取得した、それ以外のプラットフォーム固有のセキュリティ トークンを永続的に格納する&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-112">&lt;code&gt;true&lt;/code&gt; to durably store platform-specific security tokens that are obtained during login flows; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span>
            <span data-ttu-id="a8d2e-113">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-113">The default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="allowedExternalRedirectUrls"><span data-ttu-id="a8d2e-114">ログ記録や、アプリからのログ記録の一環としてにリダイレクトできる外部の Url。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-114">External URLs that can be redirected to as part of logging in or logging out of the app.</span></span> <span data-ttu-id="a8d2e-115">URL のクエリ文字列の部分は無視されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-115">Note that the query string part of the URL is ignored.</span></span>
            <span data-ttu-id="a8d2e-116">これは、通常 Windows ストア アプリケーションのバックエンドでのみ必要な高度な設定です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-116">This is an advanced setting typically only needed by Windows Store application backends.</span></span>
            <span data-ttu-id="a8d2e-117">現在のドメイン内の Url が常に暗黙的に許可されていることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-117">Note that URLs within the current domain are always implicitly allowed.</span></span></param>
        <param name="defaultProvider"><span data-ttu-id="a8d2e-118">複数のプロバイダーが構成されているときに使用する既定の認証プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-118">The default authentication provider to use when multiple providers are configured.</span></span>
            <span data-ttu-id="a8d2e-119">この設定は、複数のプロバイダーが構成され、認証されていないクライアント アクションが"RedirectToLoginPage"に設定されている場合にのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-119">This setting is only needed if multiple providers are configured and the unauthenticated client action is set to "RedirectToLoginPage".</span></span> <span data-ttu-id="a8d2e-120">使用可能な値が含まれます: 'AzureActiveDirectory'、'Facebook'、'Google'、'MicrosoftAccount'、'Twitter'</span><span class="sxs-lookup"><span data-stu-id="a8d2e-120">Possible values include: 'AzureActiveDirectory', 'Facebook', 'Google', 'MicrosoftAccount', 'Twitter'</span></span></param>
        <param name="tokenRefreshExtensionHours"><span data-ttu-id="a8d2e-121">セッション トークンは、トークンの更新の API の呼び出しに使用できるセッション トークンの有効期限後に時間数。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-121">The number of hours after session token expiration that a session token can be used to call the token refresh API.</span></span> <span data-ttu-id="a8d2e-122">既定値は 72 時間です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-122">The default is 72 hours.</span></span></param>
        <param name="clientId"><span data-ttu-id="a8d2e-123">この証明書利用者アプリケーション、client_id と呼ばれるのクライアント ID。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-123">The Client ID of this relying party application, known as the client_id.</span></span>
            <span data-ttu-id="a8d2e-124">この設定は、Azure Active Directory と OpenID 接続の認証またはその他のサード パーティ製 OpenID Connect プロバイダーを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-124">This setting is required for enabling OpenID Connection authentication with Azure Active Directory or other 3rd party OpenID Connect providers.</span></span>
            <span data-ttu-id="a8d2e-125">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-125">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span></param>
        <param name="clientSecret"><span data-ttu-id="a8d2e-126">この証明書利用者アプリケーションのクライアント シークレット (Azure Active Directory でこのも呼びますキー)。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-126">The Client Secret of this relying party application (in Azure Active Directory, this is also referred to as the Key).</span></span>
            <span data-ttu-id="a8d2e-127">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-127">This setting is optional.</span></span> <span data-ttu-id="a8d2e-128">クライアント シークレットが構成されていない場合、OpenID Connect の暗黙の認証フローを使用して、エンドユーザーを認証します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-128">If no client secret is configured, the OpenID Connect implicit auth flow is used to authenticate end users.</span></span>
            <span data-ttu-id="a8d2e-129">それ以外の場合、OpenID 接続承認コード フローはエンドユーザーを認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-129">Otherwise, the OpenID Connect Authorization Code Flow is used to authenticate end users.</span></span>
            <span data-ttu-id="a8d2e-130">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-130">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span></param>
        <param name="issuer"><span data-ttu-id="a8d2e-131">OpenID 接続 Issuer URI をこのアプリケーションのアクセス トークンを発行するエンティティを表すです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-131">The OpenID Connect Issuer URI that represents the entity which issues access tokens for this application.</span></span>
            <span data-ttu-id="a8d2e-132">この値は、URI の例: https://sts.windows.net/{テナント guid}、ディレクトリ テナントで Azure Active Directory を使用する場合またはします。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-132">When using Azure Active Directory, this value is the URI of the directory tenant, e.g. https://sts.windows.net/{tenant-guid}/.</span></span>
            <span data-ttu-id="a8d2e-133">この URI は、トークン発行者の大文字小文字を区別識別子です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-133">This URI is a case-sensitive identifier for the token issuer.</span></span>
            <span data-ttu-id="a8d2e-134">詳細については OpenID 接続探索: http://openid.net/specs/openid-connect-discovery-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-134">More information on OpenID Connect Discovery: http://openid.net/specs/openid-connect-discovery-1_0.html</span></span></param>
        <param name="allowedAudiences"><span data-ttu-id="a8d2e-135">Azure Active Directory によって発行された Jwt を検証する際に考慮する audience の値を許可します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-135">Allowed audience values to consider when validating JWTs issued by Azure Active Directory.</span></span> <span data-ttu-id="a8d2e-136">なお、&lt;コード&gt;ClientID&lt;/code&gt;値は常にこの設定に関係なく、許可されている対象ユーザーと見なされますが。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-136">Note that the &lt;code&gt;ClientID&lt;/code&gt; value is always considered an allowed audience, regardless of this setting.</span></span></param>
        <param name="additionalLoginParams"><span data-ttu-id="a8d2e-137">ユーザーに、OpenID Connect の承認エンドポイントに送信するログイン パラメーターを記録します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-137">Login parameters to send to the OpenID Connect authorization endpoint when a user logs in.</span></span> <span data-ttu-id="a8d2e-138">各パラメーターは、という形式にする必要があります"キー = 値"です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-138">Each parameter must be in the form "key=value".</span></span></param>
        <param name="googleClientId"><span data-ttu-id="a8d2e-139">OpenID 接続クライアント ID の Google web アプリケーション。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-139">The OpenID Connect Client ID for the Google web application.</span></span>
            <span data-ttu-id="a8d2e-140">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-140">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="a8d2e-141">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-141">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="googleClientSecret"><span data-ttu-id="a8d2e-142">Google web アプリケーションに関連付けられたクライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-142">The client secret associated with the Google web application.</span></span>
            <span data-ttu-id="a8d2e-143">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-143">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="a8d2e-144">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-144">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="googleOAuthScopes"><span data-ttu-id="a8d2e-145">Google のサインインの認証の一部として要求される OAuth 2.0 スコープ。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-145">The OAuth 2.0 scopes that will be requested as part of Google Sign-In authentication.</span></span>
            <span data-ttu-id="a8d2e-146">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-146">This setting is optional.</span></span> <span data-ttu-id="a8d2e-147">指定しない場合、"openid"、「プロファイル」および"email"が既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-147">If not specified, "openid", "profile", and "email" are used as default scopes.</span></span>
            <span data-ttu-id="a8d2e-148">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-148">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="facebookAppId"><span data-ttu-id="a8d2e-149">ログインに使用される、Facebook アプリのアプリ ID。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-149">The App ID of the Facebook app used for login.</span></span>
            <span data-ttu-id="a8d2e-150">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-150">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-151">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-151">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="facebookAppSecret"><span data-ttu-id="a8d2e-152">Facebook ログインに使用される、Facebook アプリのアプリのシークレット。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-152">The App Secret of the Facebook app used for Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-153">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-153">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-154">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-154">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="facebookOAuthScopes"><span data-ttu-id="a8d2e-155">Facebook ログイン認証の一部として要求される OAuth 2.0 スコープ。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-155">The OAuth 2.0 scopes that will be requested as part of Facebook Login authentication.</span></span>
            <span data-ttu-id="a8d2e-156">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-156">This setting is optional.</span></span>
            <span data-ttu-id="a8d2e-157">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-157">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="twitterConsumerKey"><span data-ttu-id="a8d2e-158">サインインに使用される Twitter アプリケーションの OAuth 1.0 a のコンシューマー キー。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-158">The OAuth 1.0a consumer key of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="a8d2e-159">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-159">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="a8d2e-160">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="a8d2e-160">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span></param>
        <param name="twitterConsumerSecret"><span data-ttu-id="a8d2e-161">サインインに使用される Twitter アプリケーションの OAuth 1.0 a コンシューマー シークレット。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-161">The OAuth 1.0a consumer secret of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="a8d2e-162">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-162">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="a8d2e-163">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="a8d2e-163">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span></param>
        <param name="microsoftAccountClientId"><span data-ttu-id="a8d2e-164">認証に使用されるアプリ用に作成された OAuth 2.0 クライアント ID。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-164">The OAuth 2.0 client ID that was created for the app used for authentication.</span></span>
            <span data-ttu-id="a8d2e-165">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-165">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-166">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="a8d2e-166">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span></param>
        <param name="microsoftAccountClientSecret"><span data-ttu-id="a8d2e-167">認証に使用されるアプリ用に作成されている OAuth 2.0 クライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-167">The OAuth 2.0 client secret that was created for the app used for authentication.</span></span>
            <span data-ttu-id="a8d2e-168">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-168">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-169">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="a8d2e-169">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span></param>
        <param name="microsoftAccountOAuthScopes"><span data-ttu-id="a8d2e-170">Microsoft アカウントの認証の一部として要求される OAuth 2.0 スコープ。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-170">The OAuth 2.0 scopes that will be requested as part of Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-171">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-171">This setting is optional.</span></span> <span data-ttu-id="a8d2e-172">指定しない場合、"wl.basic"は、既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-172">If not specified, "wl.basic" is used as the default scope.</span></span>
            <span data-ttu-id="a8d2e-173">Microsoft アカウントのスコープおよびアクセス許可のドキュメント: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span><span class="sxs-lookup"><span data-stu-id="a8d2e-173">Microsoft Account Scopes and permissions documentation: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span></span></param>
        <summary>
            <span data-ttu-id="a8d2e-174">SiteAuthSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-174">Initializes a new instance of the SiteAuthSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLoginParams">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalLoginParams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalLoginParams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AdditionalLoginParams" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLoginParams As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLoginParams : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AdditionalLoginParams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.additionalLoginParams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-175">取得またはユーザーがログインすると、OpenID Connect の認証エンドポイントに送信するログイン パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-175">Gets or sets login parameters to send to the OpenID Connect authorization endpoint when a user logs in.</span></span> <span data-ttu-id="a8d2e-176">各パラメーターは、という形式にする必要があります"キー = 値"です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-176">Each parameter must be in the form "key=value".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedAudiences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedAudiences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedAudiences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedAudiences" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedAudiences As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedAudiences : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedAudiences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedAudiences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-177">取得または Azure Active Directory によって発行された Jwt を検証する際に考慮する許可されている対象の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-177">Gets or sets allowed audience values to consider when validating JWTs issued by Azure Active Directory.</span></span> <span data-ttu-id="a8d2e-178">なお、 &amp;lt; コード&amp;gt;ClientID&amp;lt;/code&amp;gt; の値は常にこの設定に関係なく、許可されている対象ユーザーと見なされますが。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-178">Note that the &amp;lt;code&amp;gt;ClientID&amp;lt;/code&amp;gt; value is always considered an allowed audience, regardless of this setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedExternalRedirectUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedExternalRedirectUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedExternalRedirectUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedExternalRedirectUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedExternalRedirectUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedExternalRedirectUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedExternalRedirectUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedExternalRedirectUrls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-179">取得またはでのログ記録や、アプリからのログ記録の一部として外部 Url にリダイレクトできるを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-179">Gets or sets external URLs that can be redirected to as part of logging in or logging out of the app.</span></span> <span data-ttu-id="a8d2e-180">URL のクエリ文字列の部分は無視されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-180">Note that the query string part of the URL is ignored.</span></span>
            <span data-ttu-id="a8d2e-181">これは、通常 Windows ストア アプリケーションのバックエンドでのみ必要な高度な設定です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-181">This is an advanced setting typically only needed by Windows Store application backends.</span></span>
            <span data-ttu-id="a8d2e-182">現在のドメイン内の Url が常に暗黙的に許可されていることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-182">Note that URLs within the current domain are always implicitly allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-183">取得またはこの証明書利用者アプリケーション、client_id と呼ばれるは、クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-183">Gets or sets the Client ID of this relying party application, known as the client_id.</span></span>
            <span data-ttu-id="a8d2e-184">この設定は、Azure Active Directory と OpenID 接続の認証またはその他のサード パーティ製 OpenID Connect プロバイダーを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-184">This setting is required for enabling OpenID Connection authentication with Azure Active Directory or other 3rd party OpenID Connect providers.</span></span>
            <span data-ttu-id="a8d2e-185">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-185">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-186">この証明書利用者アプリケーションのクライアント シークレットの設定を取得または (Azure Active Directory でこのも呼びますキー)。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-186">Gets or sets the Client Secret of this relying party application (in Azure Active Directory, this is also referred to as the Key).</span></span>
            <span data-ttu-id="a8d2e-187">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-187">This setting is optional.</span></span> <span data-ttu-id="a8d2e-188">クライアント シークレットが構成されていない場合、OpenID Connect の暗黙の認証フローを使用して、エンドユーザーを認証します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-188">If no client secret is configured, the OpenID Connect implicit auth flow is used to authenticate end users.</span></span>
            <span data-ttu-id="a8d2e-189">それ以外の場合、OpenID 接続承認コード フローはエンドユーザーを認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-189">Otherwise, the OpenID Connect Authorization Code Flow is used to authenticate end users.</span></span>
            <span data-ttu-id="a8d2e-190">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-190">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProvider">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; DefaultProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; DefaultProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.DefaultProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProvider As Nullable(Of BuiltInAuthenticationProvider)" />
      <MemberSignature Language="F#" Value="member this.DefaultProvider : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.DefaultProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-191">取得または複数のプロバイダーが構成されているときに使用する既定の認証プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-191">Gets or sets the default authentication provider to use when multiple providers are configured.</span></span>
            <span data-ttu-id="a8d2e-192">この設定は、複数のプロバイダーが構成され、認証されていないクライアント アクションが"RedirectToLoginPage"に設定されている場合にのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-192">This setting is only needed if multiple providers are configured and the unauthenticated client action is set to "RedirectToLoginPage".</span></span> <span data-ttu-id="a8d2e-193">使用可能な値が含まれます: 'AzureActiveDirectory'、'Facebook'、'Google'、'MicrosoftAccount'、'Twitter'</span><span class="sxs-lookup"><span data-stu-id="a8d2e-193">Possible values include: 'AzureActiveDirectory', 'Facebook', 'Google', 'MicrosoftAccount', 'Twitter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-194">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt 以外の場合、認証/承認の機能は現在のアプリに対応している、それ以外の&amp;lt; コード&amp;gt; false&amp;。lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-194">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the Authentication / Authorization feature is enabled for the current app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppId">
      <MemberSignature Language="C#" Value="public string FacebookAppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppId" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppId As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookAppId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-195">取得またはログインに使用される、Facebook アプリのアプリ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-195">Gets or sets the App ID of the Facebook app used for login.</span></span>
            <span data-ttu-id="a8d2e-196">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-196">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-197">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-197">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppSecret">
      <MemberSignature Language="C#" Value="public string FacebookAppSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppSecret As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookAppSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-198">取得または Facebook のログインに使用される、Facebook アプリのアプリのシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-198">Gets or sets the App Secret of the Facebook app used for Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-199">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-199">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="a8d2e-200">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-200">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; FacebookOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; FacebookOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.FacebookOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-201">取得または Facebook ログイン認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-201">Gets or sets the OAuth 2.0 scopes that will be requested as part of Facebook Login authentication.</span></span>
            <span data-ttu-id="a8d2e-202">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-202">This setting is optional.</span></span>
            <span data-ttu-id="a8d2e-203">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="a8d2e-203">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientId">
      <MemberSignature Language="C#" Value="public string GoogleClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientId As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-204">取得または Google web アプリケーションの OpenID 接続クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-204">Gets or sets the OpenID Connect Client ID for the Google web application.</span></span>
            <span data-ttu-id="a8d2e-205">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-205">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="a8d2e-206">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-206">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientSecret">
      <MemberSignature Language="C#" Value="public string GoogleClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleClientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-207">取得または Google web アプリケーションに関連付けられたクライアント シークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-207">Gets or sets the client secret associated with the Google web application.</span></span>
            <span data-ttu-id="a8d2e-208">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-208">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="a8d2e-209">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-209">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GoogleOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GoogleOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GoogleOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-210">取得または Google のサインインの認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-210">Gets or sets the OAuth 2.0 scopes that will be requested as part of Google Sign-In authentication.</span></span>
            <span data-ttu-id="a8d2e-211">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-211">This setting is optional.</span></span> <span data-ttu-id="a8d2e-212">指定しない場合、"openid"、「プロファイル」および"email"が既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-212">If not specified, "openid", "profile", and "email" are used as default scopes.</span></span>
            <span data-ttu-id="a8d2e-213">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="a8d2e-213">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-214">取得または OpenID 接続発行者を表す URI、このアプリケーションのアクセス トークンを発行するエンティティを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-214">Gets or sets the OpenID Connect Issuer URI that represents the entity which issues access tokens for this application.</span></span>
            <span data-ttu-id="a8d2e-215">この値は、URI の例: https://sts.windows.net/{テナント guid}、ディレクトリ テナントで Azure Active Directory を使用する場合またはします。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-215">When using Azure Active Directory, this value is the URI of the directory tenant, e.g. https://sts.windows.net/{tenant-guid}/.</span></span>
            <span data-ttu-id="a8d2e-216">この URI は、トークン発行者の大文字小文字を区別識別子です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-216">This URI is a case-sensitive identifier for the token issuer.</span></span>
            <span data-ttu-id="a8d2e-217">詳細については OpenID 接続探索: http://openid.net/specs/openid-connect-discovery-1_0.html</span><span class="sxs-lookup"><span data-stu-id="a8d2e-217">More information on OpenID Connect Discovery: http://openid.net/specs/openid-connect-discovery-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientId">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientId As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-218">取得または認証に使用されるアプリの作成された OAuth 2.0 クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-218">Gets or sets the OAuth 2.0 client ID that was created for the app used for authentication.</span></span>
            <span data-ttu-id="a8d2e-219">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-219">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-220">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="a8d2e-220">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientSecret">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountClientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-221">取得または認証に使用されるアプリ用に作成されている OAuth 2.0 クライアント シークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-221">Gets or sets the OAuth 2.0 client secret that was created for the app used for authentication.</span></span>
            <span data-ttu-id="a8d2e-222">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-222">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-223">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="a8d2e-223">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; MicrosoftAccountOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-224">取得または Microsoft アカウントの認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-224">Gets or sets the OAuth 2.0 scopes that will be requested as part of Microsoft Account authentication.</span></span>
            <span data-ttu-id="a8d2e-225">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-225">This setting is optional.</span></span> <span data-ttu-id="a8d2e-226">指定しない場合、"wl.basic"は、既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-226">If not specified, "wl.basic" is used as the default scope.</span></span>
            <span data-ttu-id="a8d2e-227">Microsoft アカウントのスコープおよびアクセス許可のドキュメント: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span><span class="sxs-lookup"><span data-stu-id="a8d2e-227">Microsoft Account Scopes and permissions documentation: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-228">取得または設定、認証の RuntimeVersion/承認機能の現在のアプリケーション用に使用します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-228">Gets or sets the RuntimeVersion of the Authentication / Authorization feature in use for the current app.</span></span>
            <span data-ttu-id="a8d2e-229">この値の設定は、認証に特定の機能の動作を制御できます/承認モジュール。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-229">The setting in this value can control the behavior of certain features in the Authentication / Authorization module.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenRefreshExtensionHours">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; TokenRefreshExtensionHours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; TokenRefreshExtensionHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenRefreshExtensionHours" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenRefreshExtensionHours As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.TokenRefreshExtensionHours : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenRefreshExtensionHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenRefreshExtensionHours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-230">取得またはトークンの更新の API の呼び出しにセッション トークンを使用できるセッション トークンの有効期限後に時間数を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-230">Gets or sets the number of hours after session token expiration that a session token can be used to call the token refresh API.</span></span> <span data-ttu-id="a8d2e-231">既定値は 72 時間です。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-231">The default is 72 hours.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenStoreEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; TokenStoreEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; TokenStoreEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenStoreEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenStoreEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TokenStoreEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenStoreEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenStoreEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-232">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; ログイン フロー中に取得した、それ以外のプラットフォーム固有のセキュリティ トークンを永続的に格納する&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-232">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to durably store platform-specific security tokens that are obtained during login flows; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="a8d2e-233">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-233">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerKey">
      <MemberSignature Language="C#" Value="public string TwitterConsumerKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerKey" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerKey As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerKey : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.twitterConsumerKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-234">取得または設定のサインインに使用される Twitter アプリケーションの OAuth 1.0 a のコンシューマー キー。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-234">Gets or sets the OAuth 1.0a consumer key of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="a8d2e-235">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-235">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="a8d2e-236">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="a8d2e-236">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerSecret">
      <MemberSignature Language="C#" Value="public string TwitterConsumerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerSecret As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.twitterConsumerSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-237">取得または設定のサインインに使用される Twitter アプリケーションの OAuth 1.0 a のコンシューマー シークレット。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-237">Gets or sets the OAuth 1.0a consumer secret of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="a8d2e-238">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-238">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="a8d2e-239">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="a8d2e-239">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnauthenticatedClientAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.UnauthenticatedClientAction" />
      <MemberSignature Language="VB.NET" Value="Public Property UnauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction)" />
      <MemberSignature Language="F#" Value="member this.UnauthenticatedClientAction : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.UnauthenticatedClientAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unauthenticatedClientAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d2e-240">取得または認証されていないクライアントが、アプリにアクセスしようとしたときに実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d2e-240">Gets or sets the action to take when an unauthenticated client attempts to access the app.</span></span> <span data-ttu-id="a8d2e-241">使用可能な値が含まれます: 'RedirectToLoginPage'、'AllowAnonymous'</span><span class="sxs-lookup"><span data-stu-id="a8d2e-241">Possible values include: 'RedirectToLoginPage', 'AllowAnonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>