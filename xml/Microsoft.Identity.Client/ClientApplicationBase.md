<Type Name="ClientApplicationBase" FullName="Microsoft.Identity.Client.ClientApplicationBase">
  <TypeSignature Language="C#" Value="public abstract class ClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ClientApplicationBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ClientApplicationBase" />
  <TypeSignature Language="F#" Value="type ClientApplicationBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
    <Summary>
            <span data-ttu-id="68e6d-101">一般的な API のメソッドとプロパティを含む抽象クラスです。</span><span class="sxs-lookup"><span data-stu-id="68e6d-101">Abstract class containing common API methods and properties.</span></span> <span data-ttu-id="68e6d-102">PublicClientApplication と ConfidentialClientApplication の両方は、このクラスを拡張します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-102">Both PublicClientApplication and ConfidentialClientApplication extend this class.</span></span>
            </Summary>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ClientApplicationBase (string clientId, string authority, string redirectUri, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.#ctor(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (clientId As String, authority As String, redirectUri As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientApplicationBase : string * string * string * bool -&gt; Microsoft.Identity.Client.ClientApplicationBase" Usage="new Microsoft.Identity.Client.ClientApplicationBase (clientId, authority, redirectUri, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <param name="authority"></param>
        <param name="redirectUri"></param>
        <param name="validateAuthority"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="68e6d-103">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="68e6d-103">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="68e6d-104">トークンが要求されるユーザー。</span><span class="sxs-lookup"><span data-stu-id="68e6d-104">User for which the token is requested.</span></span> <see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <summary>
            <span data-ttu-id="68e6d-105">キャッシュからアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="68e6d-105">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="68e6d-106">要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-106">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="68e6d-107">つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="68e6d-107">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="68e6d-108">アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-108">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="68e6d-109">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="68e6d-109">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="68e6d-110">ユーザー トークンが要求されます。<see cref="T:Microsoft.Identity.Client.User" /></span><span class="sxs-lookup"><span data-stu-id="68e6d-110">User for which the token is requested <see cref="T:Microsoft.Identity.Client.User" /></span></span></param>
        <param name="authority"><span data-ttu-id="68e6d-111">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="68e6d-111">Specific authority for which the token is requested.</span></span> <span data-ttu-id="68e6d-112">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="68e6d-112">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="68e6d-113">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、使用可能な場合は、更新トークンを使用して新しいアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="68e6d-113">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using the refresh token if available</span></span></param>
        <summary>
            <span data-ttu-id="68e6d-114">キャッシュからアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="68e6d-114">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="68e6d-115">要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-115">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="68e6d-116">つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="68e6d-116">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="68e6d-117">アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-117">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <Summary>
            <span data-ttu-id="68e6d-118">ライブラリで使用される開発者または既定の機関から提供される証明機関。</span><span class="sxs-lookup"><span data-stu-id="68e6d-118">Authority provided by the developer or default authority used by the library.</span></span>
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-119">既定値になります。</span><span class="sxs-lookup"><span data-stu-id="68e6d-119">Will be a default value.</span></span> <span data-ttu-id="68e6d-120">開発者によってオーバーライドできます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-120">Can be overridden by the developer.</span></span> <span data-ttu-id="68e6d-121">一度設定したら、アプリケーションは、クライアント id。 にバインドされます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-121">Once set, application will bind to the client Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-122">使用 MSAL、およびそのコンポーネントの識別子はライブラリ/Sdk MSAL を消費するものです。</span><span class="sxs-lookup"><span data-stu-id="68e6d-122">Identifier of the component consuming MSAL and it is intended for libraries/SDKs that consume MSAL.</span></span> <span data-ttu-id="68e6d-123">これは、アプリ vs MSAL による使用量のコンポーネント ライブラリによる使用率が MSAL 間のあいまいさが許可されます。</span><span class="sxs-lookup"><span data-stu-id="68e6d-123">This will allow for disambiguation between MSAL usage by the app vs MSAL usage by component libraries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAuthority">
      <MemberSignature Language="C#" Value="protected const string DefaultAuthority;" />
      <MemberSignature Language="ILAsm" Value=".field family static literal string DefaultAuthority" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberSignature Language="VB.NET" Value="Protected Const DefaultAuthority As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultAuthority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <Summary>
            <span data-ttu-id="68e6d-124">既定の機関が対話型の呼び出しに使用します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-124">Default Authority used for interactive calls.</span></span>
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser&#xA;override this.GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="clientApplicationBase.GetUser identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.IUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="68e6d-125">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="68e6d-125">user identifier</span></span></param>
        <summary>
            <span data-ttu-id="68e6d-126">キャッシュ内に、識別子によって使用可能なユーザーからのユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-126">Get user by identifier from users available in the cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectUri">
      <MemberSignature Language="C#" Value="public string RedirectUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-127">アプリの登録ポータルで構成されている Uri にリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="68e6d-127">Redirect Uri configured in the app registration portal.</span></span> <span data-ttu-id="68e6d-128">PublicClientApplication は、urn:ietf:wg:oauth:2.0:oob の既定値があります。ライブラリがシステム webview の認証を利用する必要があると、この既定値は iOS および Android には適用されません。</span><span class="sxs-lookup"><span data-stu-id="68e6d-128">PublicClientApplication has a default value of urn:ietf:wg:oauth:2.0:oob.This default does not apply to iOS and Android as the library needs to leverage system webview for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit&#xA;override this.Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="clientApplicationBase.Remove user" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="user"><span data-ttu-id="68e6d-129">削除する必要があるユーザーのインスタンス</span><span class="sxs-lookup"><span data-stu-id="68e6d-129">instance of the user that needs to be removed</span></span></param>
        <summary>
            <span data-ttu-id="68e6d-130">指定したユーザーのすべてのキャッシュされたトークンを削除します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-130">Removes all cached tokens for the specified user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceParameters">
      <MemberSignature Language="C#" Value="public string SliceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-131">設定またはドッグフード テストを STS に送信される、カスタム クエリ パラメーターを取得します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-131">Sets or Gets the custom query parameters that may be sent to the STS for dogfood testing.</span></span> <span data-ttu-id="68e6d-132">このパラメーターは、アプリケーションに悪影響を与えるを与える可能性があります、開発者によっては設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="68e6d-132">This parameter should not be set by the developers as it may have adverse effect on the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Identity.Client.IUser&gt; Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.ClientApplicationBase.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-133">アプリケーションのキャッシュで利用可能なすべてのユーザーの一覧を提供する、キャッシュ経由でユーザー中心のビューを返します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-133">Returns a User centric view over the cache that provides a list of all the available users in the cache for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68e6d-134">取得/設定を示す値機関検証は有効になっているかどうか、または無効化します。</span><span class="sxs-lookup"><span data-stu-id="68e6d-134">Gets/sets a value indicating whether authority validation is ON or OFF.</span></span> <span data-ttu-id="68e6d-135">値は既定では true です。</span><span class="sxs-lookup"><span data-stu-id="68e6d-135">Value is true by default.</span></span> <span data-ttu-id="68e6d-136">B2C アプリケーション deveopers で false に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="68e6d-136">It should be set to false by the deveopers for B2C applications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>