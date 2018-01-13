<Type Name="IClientApplicationBase" FullName="Microsoft.Identity.Client.IClientApplicationBase">
  <TypeSignature Language="C#" Value="public interface IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IClientApplicationBase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e8811-101">共通の検証メソッドを含むコンポーネント</span><span class="sxs-lookup"><span data-stu-id="e8811-101">Component containing common validation methods</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="e8811-102">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="e8811-102">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="e8811-103">トークンが要求されるユーザー。</span><span class="sxs-lookup"><span data-stu-id="e8811-103">User for which the token is requested.</span></span> <see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <summary>
            <span data-ttu-id="e8811-104">キャッシュからアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e8811-104">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="e8811-105">要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。</span><span class="sxs-lookup"><span data-stu-id="e8811-105">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="e8811-106">つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="e8811-106">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="e8811-107">アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。</span><span class="sxs-lookup"><span data-stu-id="e8811-107">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="e8811-108">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="e8811-108">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="e8811-109">ユーザー トークンが要求されます。<see cref="T:Microsoft.Identity.Client.IUser" /></span><span class="sxs-lookup"><span data-stu-id="e8811-109">User for which the token is requested <see cref="T:Microsoft.Identity.Client.IUser" /></span></span></param>
        <param name="authority"><span data-ttu-id="e8811-110">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="e8811-110">Specific authority for which the token is requested.</span></span> <span data-ttu-id="e8811-111">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="e8811-111">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="e8811-112">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、使用可能な場合は、更新トークンを使用して新しいアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e8811-112">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using the refresh token if available</span></span></param>
        <summary>
            <span data-ttu-id="e8811-113">キャッシュからアクセス トークンを取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e8811-113">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="e8811-114">要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。</span><span class="sxs-lookup"><span data-stu-id="e8811-114">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="e8811-115">つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="e8811-115">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="e8811-116">アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。</span><span class="sxs-lookup"><span data-stu-id="e8811-116">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.Authority" />
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
            <span data-ttu-id="e8811-117">ライブラリで使用される開発者または既定の機関から提供される証明機関。</span><span class="sxs-lookup"><span data-stu-id="e8811-117">Authority provided by the developer or default authority used by the library.</span></span>
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
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
            <span data-ttu-id="e8811-118">既定値になります。</span><span class="sxs-lookup"><span data-stu-id="e8811-118">Will be a default value.</span></span> <span data-ttu-id="e8811-119">開発者によってオーバーライドできます。</span><span class="sxs-lookup"><span data-stu-id="e8811-119">Can be overridden by the developer.</span></span> <span data-ttu-id="e8811-120">一度設定したら、アプリケーションは、クライアント id。 にバインドされます。</span><span class="sxs-lookup"><span data-stu-id="e8811-120">Once set, application will bind to the client Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.Component" />
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
            <span data-ttu-id="e8811-121">使用 MSAL、およびそのコンポーネントの識別子はライブラリ/Sdk MSAL を消費するものです。</span><span class="sxs-lookup"><span data-stu-id="e8811-121">Identifier of the component consuming MSAL and it is intended for libraries/SDKs that consume MSAL.</span></span> <span data-ttu-id="e8811-122">これは、アプリ vs MSAL による使用量のコンポーネント ライブラリによる使用率が MSAL 間のあいまいさが許可されます。</span><span class="sxs-lookup"><span data-stu-id="e8811-122">This will allow for disambiguation between MSAL usage by the app vs MSAL usage by component libraries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="iClientApplicationBase.GetUser identifier" />
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
        <param name="identifier"><span data-ttu-id="e8811-123">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="e8811-123">user identifier</span></span></param>
        <summary>
            <span data-ttu-id="e8811-124">キャッシュ内に、識別子によって使用可能なユーザーからのユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8811-124">Get user by identifier from users available in the cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectUri">
      <MemberSignature Language="C#" Value="public string RedirectUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
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
            <span data-ttu-id="e8811-125">ポータルで構成された Uri にリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="e8811-125">Redirect Uri configured in the portal.</span></span> <span data-ttu-id="e8811-126">既定値になります。</span><span class="sxs-lookup"><span data-stu-id="e8811-126">Will have a default value.</span></span> <span data-ttu-id="e8811-127">開発者が、既定のクライアント id。 を使用するかどうかは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="e8811-127">Not required if the developer is using the default client Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="iClientApplicationBase.Remove user" />
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
        <param name="user"><span data-ttu-id="e8811-128">削除する必要があるユーザーのインスタンス</span><span class="sxs-lookup"><span data-stu-id="e8811-128">instance of the user that needs to be removed</span></span></param>
        <summary>
            <span data-ttu-id="e8811-129">指定したユーザーのすべてのキャッシュされたトークンを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8811-129">Removes all cached tokens for the specified user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceParameters">
      <MemberSignature Language="C#" Value="public string SliceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
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
            <span data-ttu-id="e8811-130">設定またはドッグフード テストを STS に送信される、カスタム クエリ パラメーターを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8811-130">Sets or Gets the custom query parameters that may be sent to the STS for dogfood testing.</span></span> <span data-ttu-id="e8811-131">このパラメーターは、アプリケーションに悪影響を与えるを与える可能性があります、開発者によっては設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="e8811-131">This parameter should not be set by the developers as it may have adverse effect on the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Identity.Client.IUser&gt; Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.IClientApplicationBase.Users" />
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
            <span data-ttu-id="e8811-132">キャッシュの使用可能なすべてのユーザーの一覧を提供する、キャッシュ経由でユーザー中心のビューを返します。</span><span class="sxs-lookup"><span data-stu-id="e8811-132">Returns a user-centric view over the cache that provides a list of all the available users in the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
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
            <span data-ttu-id="e8811-133">アドレスの検証は有効になっているかどうか、または無効化を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8811-133">Gets a value indicating whether address validation is ON or OFF.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>