<Type Name="TokenProvider" FullName="Microsoft.Azure.EventHubs.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider : Microsoft.Azure.EventHubs.ITokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object implements class Microsoft.Azure.EventHubs.ITokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider&#xA;Implements ITokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class&#xA;    interface ITokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.EventHubs.ITokenProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="af717-101">追加のトークン プロバイダーを実装するのには、この抽象基本クラスを拡張できます。</span><span class="sxs-lookup"><span data-stu-id="af717-101">This abstract base class can be extended to implement additional token providers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider (authContext, clientAssertionCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="af717-102">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="af717-102">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="af717-103">アサーションの証明書のクライアント資格情報でします。</span><span class="sxs-lookup"><span data-stu-id="af717-103">The client assertion certificate credential.</span></span></param>
        <summary><span data-ttu-id="af717-104">Azure Active Directory のトークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="af717-104">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="af717-105"><see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> Json web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="af717-105">The <see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider (authContext, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="af717-106">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="af717-106">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="af717-107">アプリの資格情報。</span><span class="sxs-lookup"><span data-stu-id="af717-107">The app credential.</span></span></param>
        <summary><span data-ttu-id="af717-108">Azure Active Directory のトークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="af717-108">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="af717-109"><see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> Json web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="af717-109">The <see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, userIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="af717-110">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="af717-110">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="af717-111">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="af717-111">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="af717-112">クライアント アプリケーションで redirectUri です。</span><span class="sxs-lookup"><span data-stu-id="af717-112">The redirectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="af717-113">プラットフォームのパラメーター</span><span class="sxs-lookup"><span data-stu-id="af717-113">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="af717-114">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="af717-114">User Identifier</span></span></param>
        <summary><span data-ttu-id="af717-115">Azure Active Directory のトークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="af717-115">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="af717-116"><see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> Json web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="af717-116">The <see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateManagedServiceIdentityTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateManagedServiceIdentityTokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateManagedServiceIdentityTokenProvider() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateManagedServiceIdentityTokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateManagedServiceIdentityTokenProvider () As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateManagedServiceIdentityTokenProvider : unit -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateManagedServiceIdentityTokenProvider " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="af717-117">Azure 管理サービス Id のトークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="af717-117">Creates Azure Managed Service Identity token provider.</span></span></summary>
        <returns><span data-ttu-id="af717-118"><see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> Json web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="af717-118">The <see cref="T:Microsoft.Azure.EventHubs.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="af717-119">共有アクセス署名</span><span class="sxs-lookup"><span data-stu-id="af717-119">The shared access signature</span></span></param>
        <summary>
            <span data-ttu-id="af717-120">SharedAccessSignature に基づいて TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="af717-120">Construct a TokenProvider based on a sharedAccessSignature.</span></span>
            </summary>
        <returns><span data-ttu-id="af717-121">共有アクセス署名を使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="af717-121">A TokenProvider initialized with the shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="af717-122">対応する SharedAccessKeyAuthorizationRule のキー名。</span><span class="sxs-lookup"><span data-stu-id="af717-122">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="af717-123">SharedAccessKeyAuthorizationRule に関連付けられたキー</span><span class="sxs-lookup"><span data-stu-id="af717-123">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <summary>
            <span data-ttu-id="af717-124">指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="af717-124">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="af717-125">指定された規則 Id とパスワードを使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="af717-125">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.Azure.EventHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.Azure.EventHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.Azure.EventHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.Azure.EventHubs.TokenScope -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.EventHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="af717-126">対応する SharedAccessKeyAuthorizationRule のキー名。</span><span class="sxs-lookup"><span data-stu-id="af717-126">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="af717-127">SharedAccessKeyAuthorizationRule に関連付けられたキー</span><span class="sxs-lookup"><span data-stu-id="af717-127">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenScope"><span data-ttu-id="af717-128">要求トークンの tokenScope します。</span><span class="sxs-lookup"><span data-stu-id="af717-128">The tokenScope of tokens to request.</span></span></param>
        <summary>
            <span data-ttu-id="af717-129">指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="af717-129">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="af717-130">指定された規則 Id とパスワードを使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="af717-130">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="af717-131">対応する SharedAccessKeyAuthorizationRule のキー名。</span><span class="sxs-lookup"><span data-stu-id="af717-131">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="af717-132">SharedAccessKeyAuthorizationRule に関連付けられたキー</span><span class="sxs-lookup"><span data-stu-id="af717-132">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="af717-133">トークンの time to live</span><span class="sxs-lookup"><span data-stu-id="af717-133">The token time to live</span></span></param>
        <summary>
            <span data-ttu-id="af717-134">指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="af717-134">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="af717-135">指定された規則 Id とパスワードを使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="af717-135">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.Azure.EventHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.EventHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.Azure.EventHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.Azure.EventHubs.TokenScope -&gt; Microsoft.Azure.EventHubs.TokenProvider" Usage="Microsoft.Azure.EventHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.EventHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="af717-136">対応する SharedAccessKeyAuthorizationRule のキー名。</span><span class="sxs-lookup"><span data-stu-id="af717-136">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="af717-137">SharedAccessKeyAuthorizationRule に関連付けられたキー</span><span class="sxs-lookup"><span data-stu-id="af717-137">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="af717-138">トークンの time to live</span><span class="sxs-lookup"><span data-stu-id="af717-138">The token time to live</span></span></param>
        <param name="tokenScope"><span data-ttu-id="af717-139">要求トークンの tokenScope します。</span><span class="sxs-lookup"><span data-stu-id="af717-139">The tokenScope of tokens to request.</span></span></param>
        <summary>
            <span data-ttu-id="af717-140">指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="af717-140">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="af717-141">指定された規則 Id とパスワードを使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="af717-141">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.EventHubs.ITokenProvider.GetTokenAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="af717-142">アクセス トークンが適用される URI</span><span class="sxs-lookup"><span data-stu-id="af717-142">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="af717-143">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔</span><span class="sxs-lookup"><span data-stu-id="af717-143">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="af717-144">取得、<see cref="T:Microsoft.Azure.EventHubs.SecurityToken" />指定された対象ユーザーと期間。</span><span class="sxs-lookup"><span data-stu-id="af717-144">Gets a <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>