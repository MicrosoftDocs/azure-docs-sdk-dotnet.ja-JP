<Type Name="SiteAuthSettingsInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner">
  <TypeSignature Language="C#" Value="public class SiteAuthSettingsInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteAuthSettingsInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteAuthSettingsInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteAuthSettingsInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3e327-101">Azure アプリのサービス認証の構成設定/承認の機能です。</span><span class="sxs-lookup"><span data-stu-id="3e327-101">Configuration settings for the Azure App Service Authentication / Authorization feature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettingsInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e327-102">SiteAuthSettingsInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3e327-102">Initializes a new instance of the SiteAuthSettingsInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettingsInner (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; enabled = null, string runtimeVersion = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction = null, Nullable&lt;bool&gt; tokenStoreEnabled = null, System.Collections.Generic.IList&lt;string&gt; allowedExternalRedirectUrls = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; defaultProvider = null, Nullable&lt;double&gt; tokenRefreshExtensionHours = null, string clientId = null, string clientSecret = null, string issuer = null, System.Collections.Generic.IList&lt;string&gt; allowedAudiences = null, System.Collections.Generic.IList&lt;string&gt; additionalLoginParams = null, string googleClientId = null, string googleClientSecret = null, System.Collections.Generic.IList&lt;string&gt; googleOAuthScopes = null, string facebookAppId = null, string facebookAppSecret = null, System.Collections.Generic.IList&lt;string&gt; facebookOAuthScopes = null, string twitterConsumerKey = null, string twitterConsumerSecret = null, string microsoftAccountClientId = null, string microsoftAccountClientSecret = null, System.Collections.Generic.IList&lt;string&gt; microsoftAccountOAuthScopes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; enabled, string runtimeVersion, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction, valuetype System.Nullable`1&lt;bool&gt; tokenStoreEnabled, class System.Collections.Generic.IList`1&lt;string&gt; allowedExternalRedirectUrls, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; defaultProvider, valuetype System.Nullable`1&lt;float64&gt; tokenRefreshExtensionHours, string clientId, string clientSecret, string issuer, class System.Collections.Generic.IList`1&lt;string&gt; allowedAudiences, class System.Collections.Generic.IList`1&lt;string&gt; additionalLoginParams, string googleClientId, string googleClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; googleOAuthScopes, string facebookAppId, string facebookAppSecret, class System.Collections.Generic.IList`1&lt;string&gt; facebookOAuthScopes, string twitterConsumerKey, string twitterConsumerSecret, string microsoftAccountClientId, string microsoftAccountClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; microsoftAccountOAuthScopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider},System.Nullable{System.Double},System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional enabled As Nullable(Of Boolean) = null, Optional runtimeVersion As String = null, Optional unauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction) = null, Optional tokenStoreEnabled As Nullable(Of Boolean) = null, Optional allowedExternalRedirectUrls As IList(Of String) = null, Optional defaultProvider As Nullable(Of BuiltInAuthenticationProvider) = null, Optional tokenRefreshExtensionHours As Nullable(Of Double) = null, Optional clientId As String = null, Optional clientSecret As String = null, Optional issuer As String = null, Optional allowedAudiences As IList(Of String) = null, Optional additionalLoginParams As IList(Of String) = null, Optional googleClientId As String = null, Optional googleClientSecret As String = null, Optional googleOAuthScopes As IList(Of String) = null, Optional facebookAppId As String = null, Optional facebookAppSecret As String = null, Optional facebookOAuthScopes As IList(Of String) = null, Optional twitterConsumerKey As String = null, Optional twitterConsumerSecret As String = null, Optional microsoftAccountClientId As String = null, Optional microsoftAccountClientSecret As String = null, Optional microsoftAccountOAuthScopes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner : string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; * Nullable&lt;double&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner (id, name, kind, type, enabled, runtimeVersion, unauthenticatedClientAction, tokenStoreEnabled, allowedExternalRedirectUrls, defaultProvider, tokenRefreshExtensionHours, clientId, clientSecret, issuer, allowedAudiences, additionalLoginParams, googleClientId, googleClientSecret, googleOAuthScopes, facebookAppId, facebookAppSecret, facebookOAuthScopes, twitterConsumerKey, twitterConsumerSecret, microsoftAccountClientId, microsoftAccountClientSecret, microsoftAccountOAuthScopes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="unauthenticatedClientAction" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt;" />
        <Parameter Name="tokenStoreEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="allowedExternalRedirectUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="defaultProvider" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt;" />
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
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="enabled">To be added.</param>
        <param name="runtimeVersion">To be added.</param>
        <param name="unauthenticatedClientAction">To be added.</param>
        <param name="tokenStoreEnabled">To be added.</param>
        <param name="allowedExternalRedirectUrls">To be added.</param>
        <param name="defaultProvider">To be added.</param>
        <param name="tokenRefreshExtensionHours">To be added.</param>
        <param name="clientId">To be added.</param>
        <param name="clientSecret">To be added.</param>
        <param name="issuer">To be added.</param>
        <param name="allowedAudiences">To be added.</param>
        <param name="additionalLoginParams">To be added.</param>
        <param name="googleClientId">To be added.</param>
        <param name="googleClientSecret">To be added.</param>
        <param name="googleOAuthScopes">To be added.</param>
        <param name="facebookAppId">To be added.</param>
        <param name="facebookAppSecret">To be added.</param>
        <param name="facebookOAuthScopes">To be added.</param>
        <param name="twitterConsumerKey">To be added.</param>
        <param name="twitterConsumerSecret">To be added.</param>
        <param name="microsoftAccountClientId">To be added.</param>
        <param name="microsoftAccountClientSecret">To be added.</param>
        <param name="microsoftAccountOAuthScopes">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLoginParams">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalLoginParams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalLoginParams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AdditionalLoginParams" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLoginParams As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLoginParams : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AdditionalLoginParams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-103">取得またはユーザーがログインすると、OpenID Connect の認証エンドポイントに送信するログイン パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-103">Gets or sets login parameters to send to the OpenID Connect authorization endpoint when a user logs in.</span></span> <span data-ttu-id="3e327-104">各パラメーターは、という形式にする必要があります"キー = 値"です。</span><span class="sxs-lookup"><span data-stu-id="3e327-104">Each parameter must be in the form "key=value".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedAudiences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedAudiences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedAudiences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AllowedAudiences" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedAudiences As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedAudiences : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AllowedAudiences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-105">取得または Azure Active Directory によって発行された Jwt を検証する際に考慮する許可されている対象の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-105">Gets or sets allowed audience values to consider when validating JWTs issued by Azure Active Directory.</span></span> <span data-ttu-id="3e327-106">なお、 &amp;lt; コード&amp;gt;ClientID&amp;lt;/code&amp;gt; の値は常にこの設定に関係なく、許可されている対象ユーザーと見なされますが。</span><span class="sxs-lookup"><span data-stu-id="3e327-106">Note that the &amp;lt;code&amp;gt;ClientID&amp;lt;/code&amp;gt; value is always considered an allowed audience, regardless of this setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedExternalRedirectUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedExternalRedirectUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedExternalRedirectUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AllowedExternalRedirectUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedExternalRedirectUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedExternalRedirectUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.AllowedExternalRedirectUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-107">取得またはでのログ記録や、アプリからのログ記録の一部として外部 Url にリダイレクトできるを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-107">Gets or sets external URLs that can be redirected to as part of logging in or logging out of the app.</span></span> <span data-ttu-id="3e327-108">URL のクエリ文字列の部分は無視されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3e327-108">Note that the query string part of the URL is ignored.</span></span>
            <span data-ttu-id="3e327-109">これは、通常 Windows ストア アプリケーションのバックエンドでのみ必要な高度な設定です。</span><span class="sxs-lookup"><span data-stu-id="3e327-109">This is an advanced setting typically only needed by Windows Store application backends.</span></span>
            <span data-ttu-id="3e327-110">現在のドメイン内の Url が常に暗黙的に許可されていることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3e327-110">Note that URLs within the current domain are always implicitly allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-111">取得またはこの証明書利用者アプリケーション、client_id と呼ばれるは、クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-111">Gets or sets the Client ID of this relying party application, known as the client_id.</span></span>
            <span data-ttu-id="3e327-112">この設定は、Azure Active Directory と OpenID 接続の認証またはその他のサード パーティ製 OpenID Connect プロバイダーを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-112">This setting is required for enabling OpenID Connection authentication with Azure Active Directory or other 3rd party OpenID Connect providers.</span></span>
            <span data-ttu-id="3e327-113">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="3e327-113">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-114">この証明書利用者アプリケーションのクライアント シークレットの設定を取得または (Azure Active Directory でこのも呼びますキー)。</span><span class="sxs-lookup"><span data-stu-id="3e327-114">Gets or sets the Client Secret of this relying party application (in Azure Active Directory, this is also referred to as the Key).</span></span>
            <span data-ttu-id="3e327-115">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="3e327-115">This setting is optional.</span></span> <span data-ttu-id="3e327-116">クライアント シークレットが構成されていない場合、OpenID Connect の暗黙の認証フローを使用して、エンドユーザーを認証します。</span><span class="sxs-lookup"><span data-stu-id="3e327-116">If no client secret is configured, the OpenID Connect implicit auth flow is used to authenticate end users.</span></span>
            <span data-ttu-id="3e327-117">それ以外の場合、OpenID 接続承認コード フローはエンドユーザーを認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="3e327-117">Otherwise, the OpenID Connect Authorization Code Flow is used to authenticate end users.</span></span>
            <span data-ttu-id="3e327-118">OpenID Connect の詳細について: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="3e327-118">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProvider">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; DefaultProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; DefaultProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.DefaultProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProvider As Nullable(Of BuiltInAuthenticationProvider)" />
      <MemberSignature Language="F#" Value="member this.DefaultProvider : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.DefaultProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e327-119">取得または複数のプロバイダーが構成されているときに使用する既定の認証プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-119">Gets or sets the default authentication provider to use when multiple providers are configured.</span></span>
            <span data-ttu-id="3e327-120">この設定は、複数のプロバイダーが構成され、認証されていないクライアント アクションが"RedirectToLoginPage"に設定されている場合にのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3e327-120">This setting is only needed if multiple providers are configured and the unauthenticated client action is set to "RedirectToLoginPage".</span></span> <span data-ttu-id="3e327-121">使用可能な値が含まれます: 'AzureActiveDirectory'、'Facebook'、'Google'、'MicrosoftAccount'、'Twitter'</span><span class="sxs-lookup"><span data-stu-id="3e327-121">Possible values include: 'AzureActiveDirectory', 'Facebook', 'Google', 'MicrosoftAccount', 'Twitter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-122">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt 以外の場合、認証/承認の機能は現在のアプリに対応している、それ以外の&amp;lt; コード&amp;gt; false&amp;。lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="3e327-122">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the Authentication / Authorization feature is enabled for the current app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppId">
      <MemberSignature Language="C#" Value="public string FacebookAppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookAppId" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppId As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-123">取得またはログインに使用される、Facebook アプリのアプリ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-123">Gets or sets the App ID of the Facebook app used for login.</span></span>
            <span data-ttu-id="3e327-124">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-124">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="3e327-125">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="3e327-125">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppSecret">
      <MemberSignature Language="C#" Value="public string FacebookAppSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookAppSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppSecret As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppSecret : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookAppSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-126">取得または Facebook のログインに使用される、Facebook アプリのアプリのシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-126">Gets or sets the App Secret of the Facebook app used for Facebook Login.</span></span>
            <span data-ttu-id="3e327-127">この設定は、Facebook ログインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-127">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="3e327-128">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="3e327-128">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; FacebookOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; FacebookOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.FacebookOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.FacebookOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-129">取得または Facebook ログイン認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-129">Gets or sets the OAuth 2.0 scopes that will be requested as part of Facebook Login authentication.</span></span>
            <span data-ttu-id="3e327-130">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="3e327-130">This setting is optional.</span></span>
            <span data-ttu-id="3e327-131">Facebook ログイン ドキュメント: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="3e327-131">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientId">
      <MemberSignature Language="C#" Value="public string GoogleClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientId As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-132">取得または Google web アプリケーションの OpenID 接続クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-132">Gets or sets the OpenID Connect Client ID for the Google web application.</span></span>
            <span data-ttu-id="3e327-133">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-133">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="3e327-134">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="3e327-134">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientSecret">
      <MemberSignature Language="C#" Value="public string GoogleClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientSecret : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-135">取得または Google web アプリケーションに関連付けられたクライアント シークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-135">Gets or sets the client secret associated with the Google web application.</span></span>
            <span data-ttu-id="3e327-136">この設定は、Google のサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-136">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="3e327-137">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="3e327-137">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GoogleOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GoogleOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GoogleOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.GoogleOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-138">取得または Google のサインインの認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-138">Gets or sets the OAuth 2.0 scopes that will be requested as part of Google Sign-In authentication.</span></span>
            <span data-ttu-id="3e327-139">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="3e327-139">This setting is optional.</span></span> <span data-ttu-id="3e327-140">指定しない場合、"openid"、「プロファイル」および"email"が既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="3e327-140">If not specified, "openid", "profile", and "email" are used as default scopes.</span></span>
            <span data-ttu-id="3e327-141">Google のサインイン用のドキュメント: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="3e327-141">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-142">取得または OpenID 接続発行者を表す URI、このアプリケーションのアクセス トークンを発行するエンティティを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-142">Gets or sets the OpenID Connect Issuer URI that represents the entity which issues access tokens for this application.</span></span>
            <span data-ttu-id="3e327-143">この値は、URI の例: https://sts.windows.net/{テナント guid}、ディレクトリ テナントで Azure Active Directory を使用する場合またはします。</span><span class="sxs-lookup"><span data-stu-id="3e327-143">When using Azure Active Directory, this value is the URI of the directory tenant, e.g. https://sts.windows.net/{tenant-guid}/.</span></span>
            <span data-ttu-id="3e327-144">この URI は、トークン発行者の大文字小文字を区別識別子です。</span><span class="sxs-lookup"><span data-stu-id="3e327-144">This URI is a case-sensitive identifier for the token issuer.</span></span>
            <span data-ttu-id="3e327-145">詳細については OpenID 接続探索: http://openid.net/specs/openid-connect-discovery-1_0.html</span><span class="sxs-lookup"><span data-stu-id="3e327-145">More information on OpenID Connect Discovery: http://openid.net/specs/openid-connect-discovery-1_0.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientId">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientId As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-146">取得または認証に使用されるアプリの作成された OAuth 2.0 クライアント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-146">Gets or sets the OAuth 2.0 client ID that was created for the app used for authentication.</span></span>
            <span data-ttu-id="3e327-147">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-147">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="3e327-148">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="3e327-148">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientSecret">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientSecret : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-149">取得または認証に使用されるアプリ用に作成されている OAuth 2.0 クライアント シークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-149">Gets or sets the OAuth 2.0 client secret that was created for the app used for authentication.</span></span>
            <span data-ttu-id="3e327-150">この設定は、Microsoft アカウントの認証を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-150">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="3e327-151">Microsoft アカウントの OAuth のドキュメント: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="3e327-151">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; MicrosoftAccountOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.MicrosoftAccountOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-152">取得または Microsoft アカウントの認証の一部として要求される OAuth 2.0 スコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-152">Gets or sets the OAuth 2.0 scopes that will be requested as part of Microsoft Account authentication.</span></span>
            <span data-ttu-id="3e327-153">この設定はオプションです。</span><span class="sxs-lookup"><span data-stu-id="3e327-153">This setting is optional.</span></span> <span data-ttu-id="3e327-154">指定しない場合、"wl.basic"は、既定のスコープとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="3e327-154">If not specified, "wl.basic" is used as the default scope.</span></span>
            <span data-ttu-id="3e327-155">Microsoft アカウントのスコープおよびアクセス許可のドキュメント: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span><span class="sxs-lookup"><span data-stu-id="3e327-155">Microsoft Account Scopes and permissions documentation: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-156">取得または設定、認証の RuntimeVersion/承認機能の現在のアプリケーション用に使用します。</span><span class="sxs-lookup"><span data-stu-id="3e327-156">Gets or sets the RuntimeVersion of the Authentication / Authorization feature in use for the current app.</span></span>
            <span data-ttu-id="3e327-157">この値の設定は、認証に特定の機能の動作を制御できます/承認モジュール。</span><span class="sxs-lookup"><span data-stu-id="3e327-157">The setting in this value can control the behavior of certain features in the Authentication / Authorization module.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenRefreshExtensionHours">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; TokenRefreshExtensionHours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; TokenRefreshExtensionHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TokenRefreshExtensionHours" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenRefreshExtensionHours As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.TokenRefreshExtensionHours : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TokenRefreshExtensionHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-158">取得またはトークンの更新の API の呼び出しにセッション トークンを使用できるセッション トークンの有効期限後に時間数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-158">Gets or sets the number of hours after session token expiration that a session token can be used to call the token refresh API.</span></span> <span data-ttu-id="3e327-159">既定値は 72 時間です。</span><span class="sxs-lookup"><span data-stu-id="3e327-159">The default is 72 hours.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenStoreEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; TokenStoreEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; TokenStoreEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TokenStoreEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenStoreEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TokenStoreEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TokenStoreEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-160">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; ログイン フロー中に取得した、それ以外のプラットフォーム固有のセキュリティ トークンを永続的に格納する&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="3e327-160">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to durably store platform-specific security tokens that are obtained during login flows; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="3e327-161">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="3e327-161">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerKey">
      <MemberSignature Language="C#" Value="public string TwitterConsumerKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TwitterConsumerKey" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerKey As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerKey : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TwitterConsumerKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-162">取得または設定のサインインに使用される Twitter アプリケーションの OAuth 1.0 a のコンシューマー キー。</span><span class="sxs-lookup"><span data-stu-id="3e327-162">Gets or sets the OAuth 1.0a consumer key of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="3e327-163">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-163">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="3e327-164">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="3e327-164">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerSecret">
      <MemberSignature Language="C#" Value="public string TwitterConsumerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TwitterConsumerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerSecret As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerSecret : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.TwitterConsumerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e327-165">取得または設定のサインインに使用される Twitter アプリケーションの OAuth 1.0 a のコンシューマー シークレット。</span><span class="sxs-lookup"><span data-stu-id="3e327-165">Gets or sets the OAuth 1.0a consumer secret of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="3e327-166">この設定は、Twitter でサインインを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3e327-166">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="3e327-167">Twitter のサインイン用のドキュメント: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="3e327-167">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnauthenticatedClientAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.UnauthenticatedClientAction" />
      <MemberSignature Language="VB.NET" Value="Public Property UnauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction)" />
      <MemberSignature Language="F#" Value="member this.UnauthenticatedClientAction : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteAuthSettingsInner.UnauthenticatedClientAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unauthenticatedClientAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UnauthenticatedClientAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e327-168">取得または認証されていないクライアントが、アプリにアクセスしようとしたときに実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e327-168">Gets or sets the action to take when an unauthenticated client attempts to access the app.</span></span> <span data-ttu-id="3e327-169">使用可能な値が含まれます: 'RedirectToLoginPage'、'AllowAnonymous'</span><span class="sxs-lookup"><span data-stu-id="3e327-169">Possible values include: 'RedirectToLoginPage', 'AllowAnonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>