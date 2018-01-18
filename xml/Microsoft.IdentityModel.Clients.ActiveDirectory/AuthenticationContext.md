<Type Name="AuthenticationContext" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationContext" />
  <TypeSignature Language="F#" Value="type AuthenticationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c574b-101">AuthenticationContext クラスは、Azure Active Directory と ad FS のサービスから認証トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-101">The AuthenticationContext class retrieves authentication tokens from Azure Active Directory and ADFS services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authority" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authority"><span data-ttu-id="c574b-102">トークンの発行する機関のアドレス。</span><span class="sxs-lookup"><span data-stu-id="c574b-102">Address of the authority to issue token.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-103">機関のアドレスを持つコンテキストを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="c574b-103">Constructor to create the context with the address of the authority.</span></span>
            <span data-ttu-id="c574b-104">このコンス トラクターを使用して、機関の URL の検証既定でオンに機関アドレスの検証がサポートされている場合。</span><span class="sxs-lookup"><span data-stu-id="c574b-104">Using this constructor will turn ON validation of the authority URL by default if validation is supported for the authority address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority"><span data-ttu-id="c574b-105">トークンの発行する機関のアドレス。</span><span class="sxs-lookup"><span data-stu-id="c574b-105">Address of the authority to issue token.</span></span></param>
        <param name="tokenCache"><span data-ttu-id="c574b-106">AcquireToken への呼び出しでキャッシュされたトークンの参照に使用されたトークンのキャッシュ</span><span class="sxs-lookup"><span data-stu-id="c574b-106">Token cache used to lookup cached tokens on calls to AcquireToken</span></span></param>
        <summary>
            <span data-ttu-id="c574b-107">機関のアドレスを持つコンテキストを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="c574b-107">Constructor to create the context with the address of the authority.</span></span>
            <span data-ttu-id="c574b-108">このコンス トラクターを使用して、機関の URL の検証既定でオンに機関アドレスの検証がサポートされている場合。</span><span class="sxs-lookup"><span data-stu-id="c574b-108">Using this constructor will turn ON validation of the authority URL by default if validation is supported for the authority address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="authority"><span data-ttu-id="c574b-109">トークンの発行する機関のアドレス。</span><span class="sxs-lookup"><span data-stu-id="c574b-109">Address of the authority to issue token.</span></span></param>
        <param name="validateAuthority"><span data-ttu-id="c574b-110">アドレスの検証を有効または無効にするフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="c574b-110">Flag to turn address validation ON or OFF.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-111">アドレスの検証を無効にするには、証明機関とフラグのアドレスでコンテキストを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="c574b-111">Constructor to create the context with the address of the authority and flag to turn address validation off.</span></span>
            <span data-ttu-id="c574b-112">このコンス トラクターを使用して、アドレスの検証は、オフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-112">Using this constructor, address validation can be turned off.</span></span> <span data-ttu-id="c574b-113">アドレスを検証しないセキュリティ暗黙的認識していることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="c574b-113">Make sure you are aware of the security implication of not validating the address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority"><span data-ttu-id="c574b-114">トークンの発行する機関のアドレス。</span><span class="sxs-lookup"><span data-stu-id="c574b-114">Address of the authority to issue token.</span></span></param>
        <param name="validateAuthority"><span data-ttu-id="c574b-115">アドレスの検証を有効または無効にするフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="c574b-115">Flag to turn address validation ON or OFF.</span></span></param>
        <param name="tokenCache"><span data-ttu-id="c574b-116">AcquireToken への呼び出しでキャッシュされたトークンの参照に使用されたトークンのキャッシュ</span><span class="sxs-lookup"><span data-stu-id="c574b-116">Token cache used to lookup cached tokens on calls to AcquireToken</span></span></param>
        <summary>
            <span data-ttu-id="c574b-117">アドレスの検証を無効にするには、証明機関とフラグのアドレスでコンテキストを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="c574b-117">Constructor to create the context with the address of the authority and flag to turn address validation off.</span></span>
            <span data-ttu-id="c574b-118">このコンス トラクターを使用して、アドレスの検証は、オフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-118">Using this constructor, address validation can be turned off.</span></span> <span data-ttu-id="c574b-119">アドレスを検証しないセキュリティ暗黙的認識していることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="c574b-119">Make sure you are aware of the security implication of not validating the address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-120">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-120">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-121">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-121">Identifier of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-122">デバイスの機関からのコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-122">Acquires device code from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-123">デバイスのコード、その有効期限が含まれています時間、ユーザー コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-123">It contains Device Code, its expiration time, User Code.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String, extraQueryParameters As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-124">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-124">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-125">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-125">Identifier of the client requesting the token.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="c574b-126">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-126">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="c574b-127">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-127">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-128">デバイスの機関からのコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-128">Acquires device code from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-129">デバイスのコード、その有効期限が含まれています時間、ユーザー コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-129">It contains Device Code, its expiration time, User Code.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-130">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-130">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientAssertion"><span data-ttu-id="c574b-131">トークンの取得に使用するクライアントのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-131">The client assertion to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-132">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-132">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-133">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-133">It contains Access Token and the Access Token's expiration time.</span></span> <span data-ttu-id="c574b-134">更新トークンのプロパティは、このオーバー ロードを null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-134">Refresh Token property will be null for this overload.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-135">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-135">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="c574b-136">トークンの取得に使用するクライアントの資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c574b-136">The client credential to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-137">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-137">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-138">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-138">It contains Access Token and the Access Token's expiration time.</span></span> <span data-ttu-id="c574b-139">更新トークンのプロパティは、このオーバー ロードを null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-139">Refresh Token property will be null for this overload.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-140">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-140">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCertificate"><span data-ttu-id="c574b-141">トークンの取得に使用するクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="c574b-141">The client certificate to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-142">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-142">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-143">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-143">It contains Access Token and the Access Token's expiration time.</span></span> <span data-ttu-id="c574b-144">更新トークンのプロパティは、このオーバー ロードを null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-144">Refresh Token property will be null for this overload.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-145">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-145">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientAssertion"><span data-ttu-id="c574b-146">トークンの取得に使用するクライアントのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-146">The client assertion to use for token acquisition.</span></span></param>
        <param name="userAssertion"><span data-ttu-id="c574b-147">トークンの取得に使用するユーザー アサーション (トークン) です。</span><span class="sxs-lookup"><span data-stu-id="c574b-147">The user assertion (token) to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-148">ユーザーの代理として、権限からアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-148">Acquires an access token from the authority on behalf of a user.</span></span> <span data-ttu-id="c574b-149">以前に受信したユーザー トークンを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c574b-149">It requires using a user token previously received.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-150">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-150">It contains Access Token and the Access Token's expiration time.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-151">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-151">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="c574b-152">トークンの取得に使用するクライアントの資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c574b-152">The client credential to use for token acquisition.</span></span></param>
        <param name="userAssertion"><span data-ttu-id="c574b-153">トークンの取得に使用するユーザー アサーション (トークン) です。</span><span class="sxs-lookup"><span data-stu-id="c574b-153">The user assertion (token) to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-154">ユーザーの代理として、権限からアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-154">Acquires an access token from the authority on behalf of a user.</span></span> <span data-ttu-id="c574b-155">以前に受信したユーザー トークンを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c574b-155">It requires using a user token previously received.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-156">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-156">It contains Access Token and the Access Token's expiration time.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-157">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-157">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCertificate"><span data-ttu-id="c574b-158">トークンの取得に使用するクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="c574b-158">The client certificate to use for token acquisition.</span></span></param>
        <param name="userAssertion"><span data-ttu-id="c574b-159">トークンの取得に使用するユーザー アサーション (トークン) です。</span><span class="sxs-lookup"><span data-stu-id="c574b-159">The user assertion (token) to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-160">ユーザーの代理として、権限からアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-160">Acquires an access token from the authority on behalf of a user.</span></span> <span data-ttu-id="c574b-161">以前に受信したユーザー トークンを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c574b-161">It requires using a user token previously received.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-162">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-162">It contains Access Token and the Access Token's expiration time.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-163">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-163">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-164">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-164">Identifier of the client requesting the token.</span></span></param>
        <param name="userAssertion"><span data-ttu-id="c574b-165">トークンの取得に使用するアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-165">The assertion to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-166">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-166">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-167">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-167">It contains Access Token and the Access Token's expiration time.</span></span> <span data-ttu-id="c574b-168">更新トークンのプロパティは、このオーバー ロードを null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-168">Refresh Token property will be null for this overload.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-169">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-169">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-170">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-170">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-171">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-171">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="parameters"><span data-ttu-id="c574b-172">承認に使用される追加のパラメーターを渡すことがあります PlatformParameters の種類のオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="c574b-172">An object of type PlatformParameters which may pass additional parameters used for authorization.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-173">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-173">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-174">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-174">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-175">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-175">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-176">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-176">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-177">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-177">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="parameters"><span data-ttu-id="c574b-178">承認に使用される追加のパラメーターを渡すことがあります PlatformParameters の種類のオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="c574b-178">An object of type PlatformParameters which may pass additional parameters used for authorization.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-179">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-179">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-180">DisplayableId から作成する場合、このパラメーターは事前認証のフォームのユーザー名フィールドに設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-180">If created from DisplayableId, this parameter will be used to pre-populate the username field in the authentication form.</span></span> <span data-ttu-id="c574b-181">エンドユーザーのユーザー名 フィールドを編集して、別のユーザーとして認証ことができますも注意してください。</span><span class="sxs-lookup"><span data-stu-id="c574b-181">Please note that the end user can still edit the username field and authenticate as a different user.</span></span>
            <span data-ttu-id="c574b-182">例外では、このような変更の通知を受信する場合は、型 RequiredDisplayableId UserIdentifier を作成します。</span><span class="sxs-lookup"><span data-stu-id="c574b-182">If you want to be notified of such change with an exception, create UserIdentifier with type RequiredDisplayableId.</span></span> <span data-ttu-id="c574b-183">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-183">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-184">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-184">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-185">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-185">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-186">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-186">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-187">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-187">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-188">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-188">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="parameters"><span data-ttu-id="c574b-189">承認コードを要求する対話型のフローに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c574b-189">Parameters needed for interactive flow requesting authorization code.</span></span> <span data-ttu-id="c574b-190">PlatformParameters のインスタンスを渡します。</span><span class="sxs-lookup"><span data-stu-id="c574b-190">Pass an instance of PlatformParameters.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-191">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-191">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-192">DisplayableId から作成する場合、このパラメーターは事前認証のフォームのユーザー名フィールドに設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-192">If created from DisplayableId, this parameter will be used to pre-populate the username field in the authentication form.</span></span> <span data-ttu-id="c574b-193">エンドユーザーのユーザー名 フィールドを編集して、別のユーザーとして認証ことができますも注意してください。</span><span class="sxs-lookup"><span data-stu-id="c574b-193">Please note that the end user can still edit the username field and authenticate as a different user.</span></span>
            <span data-ttu-id="c574b-194">例外では、このような変更の通知を受信する場合は、型 RequiredDisplayableId UserIdentifier を作成します。</span><span class="sxs-lookup"><span data-stu-id="c574b-194">If you want to be notified of such change with an exception, create UserIdentifier with type RequiredDisplayableId.</span></span> <span data-ttu-id="c574b-195">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-195">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="c574b-196">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-196">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="c574b-197">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-197">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-198">機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-198">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-199">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-199">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-200">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-200">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-201">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-201">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-202">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-202">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="parameters"><span data-ttu-id="c574b-203">プラットフォームの特定の引数と情報を含む PlatformParameters のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="c574b-203">Instance of PlatformParameters containing platform specific arguments and information.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-204">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-204">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-205">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-205">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="c574b-206">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-206">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="c574b-207">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-207">The parameter can be null.</span></span></param>
        <param name="claims"><span data-ttu-id="c574b-208">認証のために必要な追加のクレーム。</span><span class="sxs-lookup"><span data-stu-id="c574b-208">Additional claims that are needed for authentication.</span></span> <span data-ttu-id="c574b-209">AdalClaimChallengeException から取得しました。</span><span class="sxs-lookup"><span data-stu-id="c574b-209">Acquired from the AdalClaimChallengeException</span></span></param>
        <summary>
            <span data-ttu-id="c574b-210">認証のために必要なクレームを渡して、ユーザーに代わって、権限からアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-210">Acquires an access token from the authority on behalf of a user, passing in the necessary claims for authentication.</span></span> <span data-ttu-id="c574b-211">以前に受信したユーザー トークンを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c574b-211">It requires using a user token previously received.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-212">アクセス トークンとアクセス トークンの有効期限が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-212">It contains Access Token and the Access Token's expiration time.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-213">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-213">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-214">リダイレクト先アドレスは、認証コードを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-214">The redirect address used for obtaining authorization code.</span></span></param>
        <param name="clientAssertion"><span data-ttu-id="c574b-215">トークンの取得に使用するクライアントのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-215">The client assertion to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-216">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-216">Acquires security token from the authority using an authorization code previously received.</span></span>
            <span data-ttu-id="c574b-217">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-217">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-218">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-218">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-219">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-219">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-220">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-220">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="c574b-221">トークンの取得に使用する資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c574b-221">The credential to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-222">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-222">Acquires security token from the authority using authorization code previously received.</span></span>
            <span data-ttu-id="c574b-223">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-223">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-224">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-224">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-225">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-225">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-226">リダイレクト先アドレスは、認証コードを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-226">The redirect address used for obtaining authorization code.</span></span></param>
        <param name="clientCertificate"><span data-ttu-id="c574b-227">トークンの取得に使用するクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="c574b-227">The client certificate to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-228">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-228">Acquires security token from the authority using an authorization code previously received.</span></span>
            <span data-ttu-id="c574b-229">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-229">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-230">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-230">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-231">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-231">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-232">リダイレクト先アドレスは、認証コードを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-232">The redirect address used for obtaining authorization code.</span></span></param>
        <param name="clientAssertion"><span data-ttu-id="c574b-233">トークンの取得に使用するクライアントのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-233">The client assertion to use for token acquisition.</span></span></param>
        <param name="resource"><span data-ttu-id="c574b-234">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-234">Identifier of the target resource that is the recipient of the requested token.</span></span> <span data-ttu-id="c574b-235">AuthorizationCode の取得を先に指定した場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-235">It can be null if provided earlier to acquire authorizationCode.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-236">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-236">Acquires security token from the authority using an authorization code previously received.</span></span>
            <span data-ttu-id="c574b-237">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-237">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-238">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-238">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-239">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-239">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-240">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-240">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="c574b-241">トークンの取得に使用する資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c574b-241">The credential to use for token acquisition.</span></span></param>
        <param name="resource"><span data-ttu-id="c574b-242">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-242">Identifier of the target resource that is the recipient of the requested token.</span></span> <span data-ttu-id="c574b-243">AuthorizationCode の取得を先に指定した場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-243">It can be null if provided earlier to acquire authorizationCode.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-244">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-244">Acquires security token from the authority using an authorization code previously received.</span></span>
            <span data-ttu-id="c574b-245">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-245">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-246">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-246">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate, resource As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="c574b-247">サービスの認証エンドポイントから受信した認証コードです。</span><span class="sxs-lookup"><span data-stu-id="c574b-247">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-248">リダイレクト先アドレスは、認証コードを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-248">The redirect address used for obtaining authorization code.</span></span></param>
        <param name="clientCertificate"><span data-ttu-id="c574b-249">トークンの取得に使用するクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="c574b-249">The client certificate to use for token acquisition.</span></span></param>
        <param name="resource"><span data-ttu-id="c574b-250">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-250">Identifier of the target resource that is the recipient of the requested token.</span></span> <span data-ttu-id="c574b-251">AuthorizationCode の取得を先に指定した場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-251">It can be null if provided earlier to acquire authorizationCode.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-252">以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-252">Acquires security token from the authority using an authorization code previously received.</span></span>
            <span data-ttu-id="c574b-253">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-253">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-254">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-254">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync (Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync(class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByDeviceCodeAsync(Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByDeviceCodeAsync : Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByDeviceCodeAsync deviceCodeResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByDeviceCodeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceCodeResult" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult" />
      </Parameters>
      <Docs>
        <param name="deviceCodeResult"><span data-ttu-id="c574b-255">呼び出し元の AcquireDeviceCodeAsync から受信したデバイス コード結果。</span><span class="sxs-lookup"><span data-stu-id="c574b-255">The device code result received from calling AcquireDeviceCodeAsync.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-256">以前に受信したデバイス コードを使用して、機関からセキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-256">Acquires security token from the authority using an device code previously received.</span></span>
            <span data-ttu-id="c574b-257">このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。</span><span class="sxs-lookup"><span data-stu-id="c574b-257">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-258">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-258">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-259">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-259">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-260">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-260">Identifier of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-261">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-261">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-262">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-262">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-263">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-263">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientAssertion, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-264">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-264">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientAssertion"><span data-ttu-id="c574b-265">トークンの取得に使用するクライアントのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="c574b-265">The client assertion to use for token acquisition.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-266">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-266">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-267">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-267">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-268">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-268">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-269">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-269">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-270">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-270">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCredential, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-271">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-271">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="c574b-272">トークンの取得に使用するクライアントの資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c574b-272">The client credential to use for token acquisition.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-273">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-273">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-274">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-274">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-275">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-275">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-276">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-276">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-277">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-277">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientCertificate As IClientAssertionCertificate, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCertificate, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-278">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-278">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientCertificate"><span data-ttu-id="c574b-279">トークンの取得に使用するクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="c574b-279">The client certificate to use for token acquisition.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-280">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-280">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-281">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-281">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-282">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-282">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-283">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-283">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-284">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-284">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-285">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-285">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-286">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-286">Identifier of the client requesting the token.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-287">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-287">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-288">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-288">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-289">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-289">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-290">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-290">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-291">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-291">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-292">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-292">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-293">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-293">Identifier of the client requesting the token.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-294">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-294">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-295">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-295">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <param name="parameters"><span data-ttu-id="c574b-296">プラットフォームの特定の引数と情報を含む PlatformParameters のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="c574b-296">Instance of PlatformParameters containing platform specific arguments and information.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-297">ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-297">Acquires security token without asking for user credential.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-298">アクセス トークン、その有効期限、ユーザー情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c574b-298">It contains Access Token, its expiration time, user information.</span></span> <span data-ttu-id="c574b-299">ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c574b-299">If acquiring token without user credential is not possible, the method throws AdalException.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c574b-300">トークンの発行する機関のアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-300">Gets address of the authority to issue token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public Guid CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As Guid" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : Guid with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c574b-301">取得または設定の相関 Id とは、次の要求をサービスに送信されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-301">Gets or sets correlation Id which would be sent to the service with the next request.</span></span>
            <span data-ttu-id="c574b-302">相関 Id では、診断目的で使用します。</span><span class="sxs-lookup"><span data-stu-id="c574b-302">Correlation Id is to be used for diagnostics purposes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedLifeTimeEnabled">
      <MemberSignature Language="C#" Value="public bool ExtendedLifeTimeEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExtendedLifeTimeEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedLifeTimeEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExtendedLifeTimeEnabled : bool with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c574b-303">AAD の有効期間の延長のフラグを設定するために使用</span><span class="sxs-lookup"><span data-stu-id="c574b-303">Used to set the flag for AAD extended lifetime</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-304">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-304">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-305">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-305">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-306">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-306">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-307">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-307">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-308">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-308">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="c574b-309">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-309">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="c574b-310">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-310">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-311">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-311">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-312">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="c574b-312">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="c574b-313">要求されたトークンの受信者は、ターゲット リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-313">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="c574b-314">トークンを要求したクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="c574b-314">Identifier of the client requesting the token.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="c574b-315">機関からの応答を受信したときに戻るにはアドレスです。</span><span class="sxs-lookup"><span data-stu-id="c574b-315">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="userId"><span data-ttu-id="c574b-316">ユーザー トークンの識別子が要求されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-316">Identifier of the user token is requested for.</span></span> <span data-ttu-id="c574b-317">このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</span><span class="sxs-lookup"><span data-stu-id="c574b-317">This parameter can be <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />.Any.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="c574b-318">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="c574b-318">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="c574b-319">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c574b-319">The parameter can be null.</span></span></param>
        <param name="claims"><span data-ttu-id="c574b-320">認証のために必要な追加のクレーム。</span><span class="sxs-lookup"><span data-stu-id="c574b-320">Additional claims that are needed for authentication.</span></span> <span data-ttu-id="c574b-321">AdalClaimChallengeException から取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-321">Acquired from the AdalClaimChallengeException.</span></span> <span data-ttu-id="c574b-322">このパラメーターには、null を指定できます。</span><span class="sxs-lookup"><span data-stu-id="c574b-322">This parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="c574b-323">クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-323">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="c574b-324">クエリ パラメーターを含む authorize エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="c574b-324">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenCache">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenCache As TokenCache" />
      <MemberSignature Language="F#" Value="member this.TokenCache : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c574b-325">ADAL のトークンのキャッシュを提供するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="c574b-325">Property to provide ADAL's token cache.</span></span> <span data-ttu-id="c574b-326">プラットフォームによって TokenCache はか既定の永続的なキャッシュがあります。</span><span class="sxs-lookup"><span data-stu-id="c574b-326">Depending on the platform, TokenCache may have a default persistent cache or not.</span></span>
            <span data-ttu-id="c574b-327">それらを取得するたびにライブラリは既定の TokenCache に自動的にトークンを保存します。</span><span class="sxs-lookup"><span data-stu-id="c574b-327">Library will automatically save tokens in default TokenCache whenever you obtain them.</span></span> <span data-ttu-id="c574b-328">キャッシュされたトークンはそれらを保存するアプリケーションでのみ使用可能になります。</span><span class="sxs-lookup"><span data-stu-id="c574b-328">Cached tokens will be available only to the application that saved them.</span></span>
            <span data-ttu-id="c574b-329">キャッシュが永続的な場合に格納されているトークンは、アプリケーションの実行はよりも長くし、が後続の実行で使用できます。</span><span class="sxs-lookup"><span data-stu-id="c574b-329">If the cache is persistent, the tokens stored in it will outlive the application's execution, and will be available in subsequent runs.</span></span>
            <span data-ttu-id="c574b-330">トークン キャッシュを無効にするには、TokenCache を null に設定します。</span><span class="sxs-lookup"><span data-stu-id="c574b-330">To turn OFF token caching, set TokenCache to null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c574b-331">アドレスの検証は有効になっているかどうか、または無効化を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="c574b-331">Gets a value indicating whether address validation is ON or OFF.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>