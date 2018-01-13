<Type Name="KeyVaultClient" FullName="Microsoft.Azure.KeyVault.KeyVaultClient">
  <TypeSignature Language="C#" Value="public class KeyVaultClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;, IDisposable, Microsoft.Azure.KeyVault.IKeyVaultClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.KeyVault.KeyVaultClient&gt; implements class Microsoft.Azure.KeyVault.IKeyVaultClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultClient&#xA;Inherits ServiceClient(Of KeyVaultClient)&#xA;Implements IAzureClient, IDisposable, IKeyVaultClient" />
  <TypeSignature Language="F#" Value="type KeyVaultClient = class&#xA;    inherit ServiceClient&lt;KeyVaultClient&gt;&#xA;    interface IKeyVaultClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.KeyVault.KeyVaultClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.KeyVault.IKeyVaultClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bf282-101">暗号化キーの操作を実行し、Key Vault サービスに対する操作が資格情報コンテナーのクライアント クラスです。</span><span class="sxs-lookup"><span data-stu-id="bf282-101">Client class to perform cryptographic key operations and vault operations against the Key Vault service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            <span data-ttu-id="bf282-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-102">Optional.</span></span> <span data-ttu-id="bf282-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-104">KeyVaultClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-104">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="authenticationCallback"><span data-ttu-id="bf282-105">認証コールバック</span><span class="sxs-lookup"><span data-stu-id="bf282-105">The authentication callback</span></span></param>
        <param name="handlers"><span data-ttu-id="bf282-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-106">Optional.</span></span> <span data-ttu-id="bf282-107">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-107">The delegating handlers to add to the http client pipeline.</span></span></param>
        <summary>
            <span data-ttu-id="bf282-108">コンストラクター</span><span class="sxs-lookup"><span data-stu-id="bf282-108">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="authenticationCallback"><span data-ttu-id="bf282-109">認証コールバック</span><span class="sxs-lookup"><span data-stu-id="bf282-109">The authentication callback</span></span></param>
        <param name="httpClient"><span data-ttu-id="bf282-110">カスタマイズされた HTTP クライアント</span><span class="sxs-lookup"><span data-stu-id="bf282-110">Customized HTTP client</span></span> </param>
        <summary>
            <span data-ttu-id="bf282-111">コンストラクター</span><span class="sxs-lookup"><span data-stu-id="bf282-111">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultCredential credential, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultCredential credential, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultCredential,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultCredential * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credential, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="Microsoft.Azure.KeyVault.KeyVaultCredential" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="bf282-112">キー コンテナー操作の資格情報</span><span class="sxs-lookup"><span data-stu-id="bf282-112">Credential for key vault operations</span></span></param>
        <param name="httpClient"><span data-ttu-id="bf282-113">カスタマイズされた HTTP クライアント</span><span class="sxs-lookup"><span data-stu-id="bf282-113">Customized HTTP client</span></span> </param>
        <summary>
            <span data-ttu-id="bf282-114">コンストラクター</span><span class="sxs-lookup"><span data-stu-id="bf282-114">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="bf282-115">必須。</span><span class="sxs-lookup"><span data-stu-id="bf282-115">Required.</span></span> <span data-ttu-id="bf282-116">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="bf282-116">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="bf282-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-117">Optional.</span></span> <span data-ttu-id="bf282-118">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-118">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-119">KeyVaultClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-119">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            <span data-ttu-id="bf282-121">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-121">Optional.</span></span> <span data-ttu-id="bf282-122">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-122">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="bf282-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-123">Optional.</span></span> <span data-ttu-id="bf282-124">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-124">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-125">KeyVaultClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-125">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="bf282-126">必須。</span><span class="sxs-lookup"><span data-stu-id="bf282-126">Required.</span></span> <span data-ttu-id="bf282-127">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="bf282-127">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="bf282-128">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-128">Optional.</span></span> <span data-ttu-id="bf282-129">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-129">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="bf282-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf282-130">Optional.</span></span> <span data-ttu-id="bf282-131">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="bf282-131">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-132">KeyVaultClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-132">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-134">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-134">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-135">クライアント API のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="bf282-135">Client API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;&#xA;override this.BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;" Usage="keyVaultClient.BackupKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupKeyWithHttpMessagesAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-136">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-136">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-137">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-137">The name of the key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-138">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-140">指定したキーのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-140">Requests that a backup of the specified key be downloaded to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-141">キーのバックアップ操作は、保護された形式で、Azure Key Vault からキーをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-141">The Key Backup operation exports a key from Azure Key Vault in a protected form.</span></span> <span data-ttu-id="bf282-142">この操作では、Azure Key Vault システムの外部で使用できる形式では、キー マテリアルは返しません、返されるキー マテリアルは保護 Azure Key Vault HSM または Azure Key Vault 自体ことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-142">Note that this operation does NOT return key material in a form that can be used outside the Azure Key Vault system, the returned key material is either protected to a Azure Key Vault HSM or to Azure Key Vault itself.</span></span>
            <span data-ttu-id="bf282-143">この操作の目的は、キーのバックアップ、1 つの Azure Key Vault インスタンスでキーを生成し、別の Azure Key Vault インスタンスに復元してクライアントを許可するのにです。</span><span class="sxs-lookup"><span data-stu-id="bf282-143">The intent of this operation is to allow a client to GENERATE a key in one Azure Key Vault instance, BACKUP the key, and then RESTORE it into another Azure Key Vault instance.</span></span> <span data-ttu-id="bf282-144">バックアップ操作は、エクスポートする保護対象のフォームでは、Azure Key Vault からのすべてのキー タイプに使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-144">The BACKUP operation may be used to export, in protected form, any key type from Azure Key Vault.</span></span> <span data-ttu-id="bf282-145">キーの個別のバージョンは、バックアップすることはできません。</span><span class="sxs-lookup"><span data-stu-id="bf282-145">Individual versions of a key cannot be backed up.</span></span> <span data-ttu-id="bf282-146">バックアップ/復元は地理的な境界のみ; 内で実行できます別の地理的領域に 1 つの地理的領域からバックアップを復元できないことを意味します。</span><span class="sxs-lookup"><span data-stu-id="bf282-146">BACKUP / RESTORE can be performed within geographical boundaries only; meaning that a BACKUP from one geographical area cannot be restored to another geographical area.</span></span> <span data-ttu-id="bf282-147">たとえば、米国の地理的領域からのバックアップを EU の地理的領域に復元できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-147">For example, a backup from the US geographical area cannot be restored in an EU geographical area.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-150">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-151">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-152">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-152">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;&#xA;override this.BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;" Usage="keyVaultClient.BackupSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupSecretWithHttpMessagesAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-153">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-153">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-154">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-154">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-155">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-157">指定したシークレットのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-157">Requests that a backup of the specified secret be downloaded to the client.</span></span>
            <span data-ttu-id="bf282-158">認証:、シークレット/バックアップ権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-158">Authorization: requires the secrets/backup permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-161">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-162">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-163">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-163">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.CreateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateCertificateWithHttpMessagesAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-164">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-164">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-165">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-165">The name of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="bf282-166">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="bf282-166">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="bf282-167">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-167">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-168">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-168">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-169">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-171">新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-171">Creates a new certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-172">これが最初のバージョンである場合は、証明書リソースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-172">If this is the first version, the certificate resource is created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-175">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-176">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-177">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-177">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.CreateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, curve, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateKeyWithHttpMessagesAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-178">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-178">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-179">新しいキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-179">The name for the new key.</span></span> <span data-ttu-id="bf282-180">システムでは、新しいキーのバージョン名を生成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-180">The system will generate the version name for the new key.</span></span>
            </param>
        <param name="kty">
            <span data-ttu-id="bf282-181">作成するキーの型。</span><span class="sxs-lookup"><span data-stu-id="bf282-181">The type of key to create.</span></span> <span data-ttu-id="bf282-182">有効な値は、JsonWebKeyType を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-182">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="bf282-183">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="bf282-183">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </param>
        <param name="keySize">
            <span data-ttu-id="bf282-184">キーのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="bf282-184">The key size in bytes.</span></span> <span data-ttu-id="bf282-185">たとえば、1024 または 2048。</span><span class="sxs-lookup"><span data-stu-id="bf282-185">For example, 1024 or 2048.</span></span>
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="bf282-186">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-186">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="curve">
            <span data-ttu-id="bf282-187">楕円曲線の名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-187">Elliptic curve name.</span></span> <span data-ttu-id="bf282-188">有効な値は、JsonWebKeyCurveName を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-188">For valid values, see JsonWebKeyCurveName.</span></span> <span data-ttu-id="bf282-189">使用可能な値が含まれます: 'P-256'、'P-384'、'P-521'、'SECP256K1'</span><span class="sxs-lookup"><span data-stu-id="bf282-189">Possible values include: 'P-256', 'P-384', 'P-521', 'SECP256K1'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-190">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-192">新しいキーを作成、格納、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="bf282-192">Creates a new key, stores it, then returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-193">キーの作成処理は、Azure Key Vault 内のすべてのキー タイプの作成に使用できます。</span><span class="sxs-lookup"><span data-stu-id="bf282-193">The create key operation can be used to create any key type in Azure Key Vault.</span></span> <span data-ttu-id="bf282-194">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-194">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-195">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-195">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-196">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-196">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-197">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-197">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-198">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-199">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-199">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-200">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="bf282-200">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.DecryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DecryptWithHttpMessagesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-201">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-201">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-202">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-202">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-203">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-203">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-204">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="bf282-204">algorithm identifier.</span></span> <span data-ttu-id="bf282-205">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="bf282-205">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-206">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-208">暗号化されたデータの 1 つのブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-208">Decrypts a single block of encrypted data.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-209">DECRYPT 操作は、ターゲット暗号化キーと指定されたアルゴリズムを使用して暗号テキストの整形式ブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-209">The DECRYPT operation decrypts a well-formed block of ciphertext using the target encryption key and specified algorithm.</span></span> <span data-ttu-id="bf282-210">この操作は、ENCRYPT 操作の逆だけでデータの 1 つのブロックは、暗号化が解除された可能性があります、このブロックのサイズは対象のキーと使用するアルゴリズムによって異なります。</span><span class="sxs-lookup"><span data-stu-id="bf282-210">This operation is the reverse of the ENCRYPT operation; only a single block of data may be decrypted, the size of this block is dependent on the target key and the algorithm to be used.</span></span> <span data-ttu-id="bf282-211">DECRYPT 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-211">The DECRYPT operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-214">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-215">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-215">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-216">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-216">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateContactsWithHttpMessagesAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-217">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-217">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-218">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-218">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-220">指定されたキー コンテナーの証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-220">Deletes the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-221">指定した資格情報コンテナー証明書の証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-221">Deletes the certificate contacts for a specified key vault certificate.</span></span>
            <span data-ttu-id="bf282-222">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-222">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-223">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-223">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-224">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-224">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-225">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-225">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-226">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-226">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-227">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-227">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateIssuerWithHttpMessagesAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-228">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-228">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="bf282-229">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-229">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-230">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-232">指定された証明書の発行者を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-232">Deletes the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-233">DeleteCertificateIssuer 操作は、資格情報コンテナーから、指定された証明書の発行者を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-233">The DeleteCertificateIssuer operation permanently removes the specified certificate issuer from the vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-236">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-237">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-237">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-238">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-238">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateOperationWithHttpMessagesAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-239">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-239">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-240">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-240">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-241">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-241">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-243">指定された証明書の操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-243">Deletes the operation for a specified certificate.</span></span> <span data-ttu-id="bf282-244">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-244">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-245">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-245">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-246">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-246">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-247">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-247">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-248">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-249">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-249">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateWithHttpMessagesAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-250">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-250">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-251">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-251">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-252">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-252">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-254">指定したキー資格情報コンテナーから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-254">Deletes a certificate from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-255">関連付けられているポリシーと共に証明書オブジェクトのすべてのバージョンを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-255">Deletes all versions of a certificate object along with its associated policy.</span></span> <span data-ttu-id="bf282-256">削除証明書オブジェクトの個々 のバージョンを削除する証明書を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="bf282-256">Delete certificate cannot be used to remove individual versions of a certificate object.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-259">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-260">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-260">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-261">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-261">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.DeleteKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteKeyWithHttpMessagesAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-262">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-262">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-263">削除するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-263">The name of the key to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-264">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-264">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-265">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-266">Azure Key Vault に記憶域から任意の型のキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-266">Deletes a key of any type from storage in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-267">キーの個別のバージョンを削除するキーの削除操作を使用できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-267">The delete key operation cannot be used to remove individual versions of a key.</span></span> <span data-ttu-id="bf282-268">この操作は、キーが署名/検証、ラップ/ラップ解除または暗号化/暗号化解除操作に使用しないことを意味すると、キーに関連付けられている暗号化マテリアルを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-268">This operation removes the cryptographic material associated with the key, which means the key is not usable for Sign/Verify, Wrap/Unwrap or Encrypt/Decrypt operations.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-269">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-269">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-270">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-270">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-271">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-271">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-272">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-272">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-273">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-273">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSasDefinitionWithHttpMessagesAsync&gt;d__106))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-274">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-274">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-275">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-275">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="bf282-276">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-276">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-277">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-277">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-278">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-279">指定されたストレージ アカウントから SAS 定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-279">Deletes a SAS definition from a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-280">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-280">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-281">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-281">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-282">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-282">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-283">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-283">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-284">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-284">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.DeleteSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSecretWithHttpMessagesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-285">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-285">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-286">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-286">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-287">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-287">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-289">指定された key vault からシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-289">Deletes a secret from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-290">削除操作は、Azure Key Vault に格納されているシークレットに適用されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-290">The DELETE operation applies to any secret stored in Azure Key Vault.</span></span>
            <span data-ttu-id="bf282-291">削除は、個々 のバージョンのシークレットに適用できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-291">DELETE cannot be applied to an individual version of a secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-292">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-292">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-293">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-293">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-294">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-294">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-295">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-295">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-296">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-296">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.DeleteStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteStorageAccountWithHttpMessagesAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-297">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-297">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-298">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-298">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-299">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-299">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-300">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-300">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-301">ストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-301">Deletes a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-302">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-302">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-303">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-303">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-304">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-304">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-305">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-305">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-306">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-306">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-307">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-307">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.EncryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;EncryptWithHttpMessagesAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-308">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-308">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-309">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-309">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-310">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-310">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-311">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="bf282-311">algorithm identifier.</span></span> <span data-ttu-id="bf282-312">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="bf282-312">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-313">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-313">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-315">Key vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-315">Encrypts an arbitrary sequence of bytes using an encryption key that is stored in a key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-316">ENCRYPT 操作では、Azure Key Vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="bf282-316">The ENCRYPT operation encrypts an arbitrary sequence of bytes using an encryption key that is stored in Azure Key Vault.</span></span> <span data-ttu-id="bf282-317">暗号化操作はサイズが、対象のキーと使用する暗号化アルゴリズムに依存して、データの 1 つのブロックのみをサポートする注意してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-317">Note that the ENCRYPT operation only supports a single block of data, the size of which is dependent on the target key and the encryption algorithm to be used.</span></span> <span data-ttu-id="bf282-318">暗号化操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="bf282-318">The ENCRYPT operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using public portion of the key.</span></span> <span data-ttu-id="bf282-319">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="bf282-319">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-320">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-320">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-321">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-321">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-322">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-322">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-323">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-323">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-324">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-324">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-325">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="bf282-325">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="bf282-326">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="bf282-326">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.GetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateContactsWithHttpMessagesAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-327">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-327">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-328">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-328">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-329">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-329">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-330">指定されたキー コンテナーの証明書の連絡先の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-330">Lists the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-331">GetCertificateContacts 操作は、指定されたキー コンテナーに証明書の連絡先のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="bf282-331">The GetCertificateContacts operation returns the set of certificate contact resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-332">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-332">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-333">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-333">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-334">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-334">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-335">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-335">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-336">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-336">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersNextWithHttpMessagesAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-337">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-337">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-338">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-338">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-340">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="bf282-340">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-341">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-341">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-342">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-342">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-343">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-343">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-344">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-344">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-345">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-345">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-346">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-346">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersWithHttpMessagesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-347">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-347">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-348">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-348">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-349">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-349">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-350">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-350">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-351">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-351">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-352">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="bf282-352">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-353">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-353">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-354">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-354">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-355">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-355">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-356">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-356">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-357">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-357">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-358">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-358">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuerWithHttpMessagesAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-359">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-359">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="bf282-360">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-360">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-361">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-361">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-362">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-362">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-363">指定された証明書の発行者の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-363">Lists the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-364">GetCertificateIssuer 操作は、指定されたキー コンテナーに指定された証明書発行者リソースを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-364">The GetCertificateIssuer operation returns the specified certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-365">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-365">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-366">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-366">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-367">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-367">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-368">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-368">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-369">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-369">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.GetCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateOperationWithHttpMessagesAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-370">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-370">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-371">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-371">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-372">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-372">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-373">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-373">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-374">指定された証明書に関連付けられている操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-374">Gets the operation associated with a specified certificate.</span></span> <span data-ttu-id="bf282-375">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-375">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-376">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-376">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-377">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-377">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-378">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-378">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-379">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-379">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-380">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-380">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.GetCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatePolicyWithHttpMessagesAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-381">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-381">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-382">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-382">The name of the certificate in a given key vault.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-383">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-383">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-384">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-384">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-385">証明書のポリシーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-385">Lists the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-386">GetCertificatePolicy 操作は、指定されたキー コンテナーに指定された証明書ポリシー リソースを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-386">The GetCertificatePolicy operation returns the specified certificate policy resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-387">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-387">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-388">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-388">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-389">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-389">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-390">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-390">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-391">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-391">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesNextWithHttpMessagesAsync&gt;d__116))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-392">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-392">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-393">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-393">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-394">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-395">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="bf282-395">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-396">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="bf282-396">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-397">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-397">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-398">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-398">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-399">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-399">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-400">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-400">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-401">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-401">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesWithHttpMessagesAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-402">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-402">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-403">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-403">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-404">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-404">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-405">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-405">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-406">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-406">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-407">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="bf282-407">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-408">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="bf282-408">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-409">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-409">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-410">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-410">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-411">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-411">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-412">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-412">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-413">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-413">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsNextWithHttpMessagesAsync&gt;d__118))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-414">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-414">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-415">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-415">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-416">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-416">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-417">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-417">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-418">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-418">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-419">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-419">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-420">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-420">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-421">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-421">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-422">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-422">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-423">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-423">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsWithHttpMessagesAsync (vaultBaseUrl, certificateName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsWithHttpMessagesAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-424">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-424">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-425">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-425">The name of the certificate.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-426">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-426">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-427">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-427">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-428">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-428">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-429">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-430">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-430">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-431">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="bf282-431">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-432">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-432">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-433">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-433">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-434">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-434">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-435">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-435">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-436">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-436">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateWithHttpMessagesAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-437">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-437">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-438">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-438">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="bf282-439">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-439">The version of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-440">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-440">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-441">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-441">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-442">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-442">Gets information about a specified certificate.</span></span> <span data-ttu-id="bf282-443">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-443">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-444">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-444">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-445">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-445">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-446">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-446">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-447">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-447">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-448">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-448">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesNextWithHttpMessagesAsync&gt;d__119))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-449">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-449">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-450">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-450">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-451">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-452">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-452">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-453">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-453">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-454">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-454">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-455">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-455">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-456">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-456">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-457">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-457">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-458">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-458">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesWithHttpMessagesAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-459">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-459">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-460">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-460">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-461">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-461">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-462">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-462">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-463">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-464">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-464">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-465">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-465">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-466">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-466">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-467">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-467">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-468">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-468">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-469">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-469">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-470">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-470">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificateWithHttpMessagesAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-471">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-471">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-472">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="bf282-472">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-473">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-473">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-474">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-474">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-475">指定された削除済み証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-475">Retrieves information about the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-476">GetDeletedCertificate 操作は、削除された証明書の情報と保有期間、スケジュールされた永続的な削除、および現在の回復レベルでの削除など、その属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-476">The GetDeletedCertificate operation retrieves the deleted certificate information plus its attributes, such as retention interval, scheduled permanent deletion and the current deletion recovery level.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-477">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-477">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-478">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-478">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-479">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-479">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-480">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-480">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-481">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-481">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysNextWithHttpMessagesAsync&gt;d__112))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-482">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-482">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-483">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-483">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-484">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-484">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-485">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="bf282-485">List deleted keys in the specified vault.</span></span> <span data-ttu-id="bf282-486">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-486">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-487">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-487">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-488">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-488">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-489">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-489">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-490">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-490">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-491">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-491">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysWithHttpMessagesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-492">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-492">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-493">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-493">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-494">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-494">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-495">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-495">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-496">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-496">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-497">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="bf282-497">List deleted keys in the specified vault.</span></span> <span data-ttu-id="bf282-498">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-498">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-499">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-499">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-500">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-500">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-501">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-501">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-502">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-502">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-503">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-503">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeyWithHttpMessagesAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-504">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-504">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-505">キーの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-505">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-506">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-506">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-507">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-507">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-508">削除済みのキー情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-508">Retrieves the deleted key information plus its attributes.</span></span> <span data-ttu-id="bf282-509">認証:、キー/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-509">Authorization: Requires the keys/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-510">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-510">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-511">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-511">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-512">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-512">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-513">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-513">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-514">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-514">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsNextWithHttpMessagesAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-515">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-515">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-516">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-516">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-517">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-517">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-518">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-518">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="bf282-519">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-519">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-520">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-520">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-521">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-521">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-522">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-522">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-523">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-523">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-524">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-524">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsWithHttpMessagesAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-525">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-525">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-526">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-526">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-527">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-527">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-528">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-528">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-529">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-529">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-530">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-530">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="bf282-531">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-531">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-532">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-532">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-533">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-533">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-534">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-534">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-535">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-535">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-536">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-536">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretWithHttpMessagesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-537">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-537">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-538">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-538">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-539">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-539">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-540">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-540">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-541">削除された秘密情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-541">Retrieves the deleted secret information plus its attributes.</span></span>
            <span data-ttu-id="bf282-542">認証:、シークレット/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-542">Authorization: requires the secrets/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-543">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-543">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-544">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-544">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-545">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-545">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-546">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-546">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-547">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-547">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysNextWithHttpMessagesAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-548">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-548">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-549">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-549">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-550">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-550">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-551">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-551">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-552">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-552">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="bf282-553">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="bf282-553">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="bf282-554">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="bf282-554">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="bf282-555">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-555">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-556">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-556">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-557">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-557">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-558">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-558">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-559">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-559">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-560">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-560">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysWithHttpMessagesAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-561">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-561">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-562">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-562">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-563">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-563">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-564">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-564">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-565">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-565">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-566">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-566">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-567">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-567">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="bf282-568">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="bf282-568">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="bf282-569">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="bf282-569">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="bf282-570">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-570">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-571">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-571">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-572">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-572">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-573">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-573">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-574">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-574">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-575">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-575">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsNextWithHttpMessagesAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-576">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-576">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-577">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-577">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-578">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-578">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-579">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-579">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-580">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-580">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-581">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-581">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-582">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-582">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-583">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-583">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-584">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-584">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-585">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-585">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync(string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsWithHttpMessagesAsync (vaultBaseUrl, keyName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsWithHttpMessagesAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-586">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-586">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-587">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-587">The name of the key.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-588">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-588">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-589">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-589">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-590">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-590">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-591">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-591">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-592">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-592">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-593">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-593">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-594">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-594">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-595">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-595">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-596">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-596">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-597">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-597">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-598">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-598">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.GetKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-599">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-599">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-600">取得するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-600">The name of the key to get.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-601">バージョン パラメーターを追加するには、特定のバージョンのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-601">Adding the version parameter retrieves a specific version of a key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-602">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-602">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-603">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-603">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-604">格納されているキーのパブリックの部分を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-604">Gets the public part of a stored key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-605">キーの取得操作は、すべてのキー タイプに適用できます。</span><span class="sxs-lookup"><span data-stu-id="bf282-605">The get key operation is applicable to all key types.</span></span> <span data-ttu-id="bf282-606">要求されたキーが対称の場合は、し、キー マテリアルではリリースされません応答します。</span><span class="sxs-lookup"><span data-stu-id="bf282-606">If the requested key is symmetric, then no key material is released in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-607">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-607">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-608">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-608">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-609">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-609">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-610">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-610">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-611">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-611">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;&#xA;override this.GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="keyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetPendingCertificateSigningRequestWithHttpMessagesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-612">資格情報コンテナー名、https://myvault.vault.azure.net 例:</span><span class="sxs-lookup"><span data-stu-id="bf282-612">The vault name, e.g. https://myvault.vault.azure.net</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-613">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="bf282-613">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-614">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-614">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-615">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-615">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-616">保留中の証明書要求応答の署名を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-616">Gets the pending certificate signing request response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="bf282-617">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-617">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsNextWithHttpMessagesAsync&gt;d__121))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-618">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-618">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-619">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-619">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-620">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-620">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-621">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-621">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-622">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-622">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-623">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-623">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-624">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-624">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-625">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-625">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-626">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-626">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsWithHttpMessagesAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-627">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-627">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-628">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-628">The name of the storage account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-629">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-629">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-630">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-630">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-631">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-631">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-632">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-632">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-633">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-633">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-634">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-634">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-635">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-635">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-636">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-636">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-637">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-637">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-638">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-638">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionWithHttpMessagesAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-639">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-639">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-640">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-640">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="bf282-641">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-641">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-642">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-642">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-643">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-643">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-644">指定されたストレージ アカウントの SAS の定義に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-644">Gets information about a SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-645">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-645">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-646">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-646">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-647">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-647">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-648">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-648">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-649">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-649">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsNextWithHttpMessagesAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-650">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-650">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-651">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-651">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-652">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-652">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-653">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="bf282-653">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-654">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="bf282-654">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="bf282-655">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="bf282-655">Individual secret versions are not listed in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-656">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-656">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-657">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-657">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-658">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-658">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-659">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-659">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-660">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-660">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsWithHttpMessagesAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-661">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-661">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-662">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-662">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-663">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-663">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-664">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-664">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-665">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-665">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-666">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="bf282-666">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-667">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="bf282-667">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="bf282-668">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="bf282-668">Individual secret versions are not listed in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-669">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-669">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-670">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-670">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-671">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-671">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-672">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-672">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-673">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-673">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsNextWithHttpMessagesAsync&gt;d__114))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-674">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-674">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-675">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-675">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-676">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-676">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-677">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-677">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-678">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="bf282-678">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="bf282-679">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-679">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="bf282-680">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-680">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-681">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-681">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-682">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-682">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-683">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-683">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-684">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-684">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-685">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-685">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync (string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync(string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsWithHttpMessagesAsync (vaultBaseUrl, secretName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsWithHttpMessagesAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-686">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-686">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-687">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-687">The name of the secret.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-688">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-688">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-689">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-689">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-690">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-690">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-691">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-691">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-692">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-692">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-693">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="bf282-693">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="bf282-694">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-694">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="bf282-695">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-695">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-696">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-696">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-697">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-697">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-698">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-698">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-699">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-699">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-700">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-700">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.GetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretWithHttpMessagesAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-701">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-701">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-702">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-702">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="bf282-703">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-703">The version of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-704">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-704">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-705">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-705">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-706">指定されたキー コンテナーから、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-706">Get a specified secret from a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-707">GET 操作は、Azure Key Vault に格納されているシークレットに適用します。</span><span class="sxs-lookup"><span data-stu-id="bf282-707">The GET operation is applicable to any secret stored in Azure Key Vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-708">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-708">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-709">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-709">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-710">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-710">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-711">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-711">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-712">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-712">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsNextWithHttpMessagesAsync&gt;d__120))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="bf282-713">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bf282-713">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-714">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-714">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-715">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-715">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-716">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="bf282-716">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-717">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-717">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-718">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-718">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-719">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-719">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-720">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-720">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-721">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-721">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsWithHttpMessagesAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-722">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-722">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="bf282-723">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf282-723">Maximum number of results to return in a page.</span></span> <span data-ttu-id="bf282-724">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="bf282-724">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-725">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-725">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-726">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-726">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-727">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="bf282-727">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-728">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-728">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-729">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-729">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-730">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-730">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-731">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-731">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-732">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-732">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.GetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountWithHttpMessagesAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-733">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-733">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-734">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-734">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-735">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-735">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-736">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-736">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-737">指定されたストレージ アカウントの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf282-737">Gets information about a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-738">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-738">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-739">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-739">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-740">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-740">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-741">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-741">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-742">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-742">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.ImportCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportCertificateWithHttpMessagesAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-743">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-743">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-744">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-744">The name of the certificate.</span></span>
            </param>
        <param name="base64EncodedCertificate">
            <span data-ttu-id="bf282-745">インポートする証明書オブジェクトの表現を Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-745">Base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="bf282-746">この証明書を秘密キーを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-746">This certificate needs to contain the private key.</span></span>
            </param>
        <param name="password">
            <span data-ttu-id="bf282-747">Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。</span><span class="sxs-lookup"><span data-stu-id="bf282-747">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="bf282-748">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="bf282-748">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="bf282-749">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-749">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-750">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-750">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-751">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-751">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-752">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-752">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-753">指定したキー資格情報コンテナーに証明書をインポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-753">Imports a certificate into a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-754">既存有効な証明書を Azure Key Vault には秘密キーを含むをインポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-754">Imports an existing valid certificate, containing a private key, into Azure Key Vault.</span></span> <span data-ttu-id="bf282-755">インポートする証明書は、PFX または PEM のいずれかの形式であることができます。</span><span class="sxs-lookup"><span data-stu-id="bf282-755">The certificate to be imported can be in either PFX or PEM format.</span></span> <span data-ttu-id="bf282-756">キーだけでなく x509 PEM ファイルを含める必要があります PEM 形式での証明書がある場合の証明書。</span><span class="sxs-lookup"><span data-stu-id="bf282-756">If the certificate is in PEM format the PEM file must contain the key as well as x509 certificates.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-757">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-757">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-758">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-758">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-759">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-759">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-760">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-760">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-761">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-761">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.ImportKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportKeyWithHttpMessagesAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-762">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-762">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-763">インポートしたキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-763">Name for the imported key.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="bf282-764">Json web key</span><span class="sxs-lookup"><span data-stu-id="bf282-764">The Json web key</span></span>
            </param>
        <param name="hsm">
            <span data-ttu-id="bf282-765">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。</span><span class="sxs-lookup"><span data-stu-id="bf282-765">Whether to import as a hardware key (HSM) or software key.</span></span>
            </param>
        <param name="keyAttributes">
            <span data-ttu-id="bf282-766">キー管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="bf282-766">The key management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-767">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-767">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-768">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-768">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-769">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-769">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-770">外部で作成されたキーをインポートする格納し、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="bf282-770">Imports an externally created key, stores it, and returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-771">インポート キー操作は、すべてのキー タイプを Azure Key Vault にインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-771">The import key operation may be used to import any key type into an Azure Key Vault.</span></span> <span data-ttu-id="bf282-772">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-772">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-773">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-773">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-774">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-774">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-775">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-775">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-776">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-776">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-777">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-777">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-778">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-778">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="bf282-779">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="bf282-779">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.MergeCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;MergeCertificateWithHttpMessagesAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-780">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-780">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-781">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-781">The name of the certificate.</span></span>
            </param>
        <param name="x509Certificates">
            <span data-ttu-id="bf282-782">証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="bf282-782">The certificate or the certificate chain to merge.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="bf282-783">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-783">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-784">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-784">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-785">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-785">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-786">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-786">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-787">既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="bf282-787">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-788">MergeCertificate 操作では、証明書またはサービスで現在使用できるキーのペアで証明書チェーンのマージを実行します。</span><span class="sxs-lookup"><span data-stu-id="bf282-788">The MergeCertificate operation performs the merging of a certificate or certificate chain with a key pair currently available in the service.</span></span>
            <span data-ttu-id="bf282-789">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-789">Authorization: requires the certificates/update permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-790">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-790">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-791">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-791">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-792">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-792">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-793">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-793">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-794">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-794">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedCertificateWithHttpMessagesAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-795">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-795">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-796">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="bf282-796">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-797">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-797">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-798">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-798">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-799">指定された削除済み証明書を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-799">Permanently deletes the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-800">PurgeDeletedCertificate 操作では、指定された証明書を回復する可能性の元に戻すことの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="bf282-800">The PurgeDeletedCertificate operation performs an irreversible deletion of the specified certificate, without possibility for recovery.</span></span> <span data-ttu-id="bf282-801">操作は回復レベルで 'Purgeable' が指定されていない場合に使用できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-801">The operation is not available if the recovery level does not specify 'Purgeable'.</span></span>
            <span data-ttu-id="bf282-802">明示的な '削除' 権限を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-802">Requires the explicit granting of the 'purge' permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-803">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-803">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-804">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-804">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-805">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-805">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-806">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-806">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedKeyWithHttpMessagesAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-807">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-807">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-808">キーの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-808">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-809">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-809">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-810">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-810">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-811">指定したキーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-811">Permanently deletes the specified key.</span></span> <span data-ttu-id="bf282-812">別名、キーを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-812">aka purges the key.</span></span> <span data-ttu-id="bf282-813">認証:、キー/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-813">Authorization: Requires the keys/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-814">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-814">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-815">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-815">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-816">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-816">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-817">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-817">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedSecretWithHttpMessagesAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-818">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-818">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-819">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-819">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-820">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-820">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-821">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-821">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-822">指定されたシークレットを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-822">Permanently deletes the specified secret.</span></span> <span data-ttu-id="bf282-823">別名、シークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-823">aka purges the secret.</span></span>
            <span data-ttu-id="bf282-824">認証:、シークレット/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-824">Authorization: requires the secrets/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-825">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-825">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-826">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-826">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-827">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-827">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-828">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-828">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedCertificateWithHttpMessagesAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-829">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-829">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-830">削除済みの証明書の名前</span><span class="sxs-lookup"><span data-stu-id="bf282-830">The name of the deleted certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-831">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-831">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-832">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-832">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-833">現在のバージョンに戻す、削除された証明書を回復します。</span><span class="sxs-lookup"><span data-stu-id="bf282-833">Recovers the deleted certificate back to its current version under /certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-834">RecoverDeletedCertificate 操作では、削除操作の取り消しを実行します。</span><span class="sxs-lookup"><span data-stu-id="bf282-834">The RecoverDeletedCertificate operation performs the reversal of the Delete operation.</span></span> <span data-ttu-id="bf282-835">操作は、ソフト削除の有効な資格情報コンテナーに適用し、間隔、保有期間 (削除済み証明書の属性で使用可能) 発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-835">The operation is applicable in vaults enabled for soft-delete, and must be issued during the retention interval (available in the deleted certificate's attributes).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-836">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-836">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-837">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-837">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-838">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-838">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-839">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-839">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-840">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-840">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedKeyWithHttpMessagesAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-841">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-841">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-842">削除されたキーの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-842">The name of the deleted key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-843">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-843">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-844">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-844">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-845">削除されたキーに戻します/keys 下にある現在のバージョンを回復します。</span><span class="sxs-lookup"><span data-stu-id="bf282-845">Recovers the deleted key back to its current version under /keys.</span></span>
            <span data-ttu-id="bf282-846">認証:、キー/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-846">Authorization: Requires the keys/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-847">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-847">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-848">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-848">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-849">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-849">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-850">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-850">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-851">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-851">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedSecretWithHttpMessagesAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-852">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-852">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-853">削除されたシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="bf282-853">The name of the deleted secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-854">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-854">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-855">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-855">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-856">/Secrets 下にある現在のバージョンに削除されたシークレット バックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="bf282-856">Recovers the deleted secret back to its current version under /secrets.</span></span>
            <span data-ttu-id="bf282-857">認証:、シークレット/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-857">Authorization: requires the secrets/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-858">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-858">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-859">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-859">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-860">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-860">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-861">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-861">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-862">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-862">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RegenerateStorageAccountKeyWithHttpMessagesAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-863">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-863">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-864">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-864">The name of the storage account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-865">ストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-865">The storage account key name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-866">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-866">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-867">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-867">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-868">指定されたストレージ アカウントの指定したキー値を再生成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-868">Regenerates the specified key value for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-869">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-869">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-870">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-870">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-871">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-871">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-872">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-872">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-873">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-873">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync (string vaultBaseUrl, byte[] keyBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] keyBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RestoreKeyWithHttpMessagesAsync (vaultBaseUrl, keyBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreKeyWithHttpMessagesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-874">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-874">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyBundleBackup">
            <span data-ttu-id="bf282-875">キーのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="bf282-875">The backup blob associated with a key bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-876">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-876">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-877">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-877">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-878">資格情報コンテナーにキーをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="bf282-878">Restores a backed up key to a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-879">Azure Key Vault、キー、そのキー識別子、属性、およびアクセス制御ポリシーを復元するのには、以前にバックアップ キーをインポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-879">Imports a previously backed up key into Azure Key Vault, restoring the key, its key identifier, attributes and access control policies.</span></span> <span data-ttu-id="bf282-880">復元操作は、以前にバックアップ キーをインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-880">The RESTORE operation may be used to import a previously backed up key.</span></span> <span data-ttu-id="bf282-881">キーの個別のバージョンを復元することはできません。</span><span class="sxs-lookup"><span data-stu-id="bf282-881">Individual versions of a key cannot be restored.</span></span> <span data-ttu-id="bf282-882">キーにはバックアップ時と同じキー名で全体として復元されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-882">The key is restored in its entirety with the same key name as it had when it was backed up.</span></span> <span data-ttu-id="bf282-883">キー名をターゲット Key Vault では使用できない場合、復元操作は拒否されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-883">If the key name is not available in the target Key Vault, the RESTORE operation will be rejected.</span></span> <span data-ttu-id="bf282-884">キー名は、復元中に保持されますが、中に、最終的なキー識別子は、別の資格情報コンテナーにキーを復元した場合に変更されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-884">While the key name is retained during restore, the final key identifier will change if the key is restored to a different vault.</span></span> <span data-ttu-id="bf282-885">復元では、すべてのバージョンを復元し、バージョン識別子を保持します。</span><span class="sxs-lookup"><span data-stu-id="bf282-885">Restore will restore all versions and preserve version identifiers.</span></span> <span data-ttu-id="bf282-886">復元操作のセキュリティの制約があります。 ターゲット Key Vault はソース Key Vault、ユーザーがターゲット Key Vault で復元権限を必要と同じ Microsoft Azure サブスクリプションで所有する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-886">The RESTORE operation is subject to security constraints: The target Key Vault must be owned by the same Microsoft Azure Subscription as the source Key Vault The user must have RESTORE permission in the target Key Vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-887">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-887">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-888">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-888">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-889">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-889">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-890">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-890">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-891">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-891">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync (string vaultBaseUrl, byte[] secretBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] secretBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RestoreSecretWithHttpMessagesAsync (vaultBaseUrl, secretBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreSecretWithHttpMessagesAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-892">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-892">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretBundleBackup">
            <span data-ttu-id="bf282-893">シークレットのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="bf282-893">The backup blob associated with a secret bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-894">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-894">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-895">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-895">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-896">資格情報コンテナーにシークレットをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="bf282-896">Restores a backed up secret to a vault.</span></span> <span data-ttu-id="bf282-897">認証:、シークレット/復元権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-897">Authorization: requires the secrets/restore permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-898">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-898">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-899">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-899">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-900">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-900">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-901">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-901">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-902">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-902">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf282-903">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-903">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.SetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, contacts, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateContactsWithHttpMessagesAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-904">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-904">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="contacts">
            <span data-ttu-id="bf282-905">キー コンテナーの証明書の連絡先。</span><span class="sxs-lookup"><span data-stu-id="bf282-905">The contacts for the key vault certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-906">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-906">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-907">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-907">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-908">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-908">Sets the certificate contacts for the specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-909">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-909">Sets the certificate contacts for the specified key vault.</span></span> <span data-ttu-id="bf282-910">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-910">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-911">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-911">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-912">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-912">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-913">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-913">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-914">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-914">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-915">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-915">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.SetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateIssuerWithHttpMessagesAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-916">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-916">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="bf282-917">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-917">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="bf282-918">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="bf282-918">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="bf282-919">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="bf282-919">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="bf282-920">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="bf282-920">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="bf282-921">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-921">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-922">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-922">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-923">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-923">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-924">指定された証明書の発行者を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-924">Sets the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-925">SetCertificateIssuer 操作を追加または指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-925">The SetCertificateIssuer operation adds or updates the specified certificate issuer.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-926">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-926">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-927">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-927">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-928">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-928">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-929">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-929">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-930">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-930">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.SetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSasDefinitionWithHttpMessagesAsync&gt;d__108))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-931">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-931">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-932">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-932">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="bf282-933">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-933">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bf282-934">Sas 定義は、キー/値ペアの形式でのメタデータを作成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-934">Sas definition creation metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="bf282-935">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="bf282-935">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-936">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-936">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-937">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-937">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-938">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-938">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-939">作成するか、指定されたストレージ アカウントに対して新しい SAS 定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-939">Creates or updates a new SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-940">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-940">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-941">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-941">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-942">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-942">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-943">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-943">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-944">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-944">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.SetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSecretWithHttpMessagesAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-945">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-945">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-946">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-946">The name of the secret.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="bf282-947">シークレットの値です。</span><span class="sxs-lookup"><span data-stu-id="bf282-947">The value of the secret.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-948">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-948">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="bf282-949">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="bf282-949">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="bf282-950">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="bf282-950">The secret management attributes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-951">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-951">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-952">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-952">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-953">指定された key vault のシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-953">Sets a secret in a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-954">設定操作では、Azure Key Vault にシークレットを追加します。</span><span class="sxs-lookup"><span data-stu-id="bf282-954">The SET operation adds a secret to the Azure Key Vault.</span></span> <span data-ttu-id="bf282-955">名前付きのシークレットが既に存在する場合、Azure Key Vault はシークレットの新しいバージョンを作成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-955">If the named secret already exists, Azure Key Vault creates a new version of that secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-956">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-956">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-957">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-957">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-958">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-958">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-959">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-959">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-960">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-960">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.SetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetStorageAccountWithHttpMessagesAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-961">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-961">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-962">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-962">The name of the storage account.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="bf282-963">ストレージ アカウントのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="bf282-963">Storage account resource id.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="bf282-964">現在アクティブなストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-964">Current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="bf282-965">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-965">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="bf282-966">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="bf282-966">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="bf282-967">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-967">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-968">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-968">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-969">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-969">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-970">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-970">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-971">作成するか、新しいストレージ アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-971">Creates or updates a new storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-972">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-972">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-973">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-973">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-974">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-974">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-975">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-975">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-976">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-976">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SignWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.SignWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SignWithHttpMessagesAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-977">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-977">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-978">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-978">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-979">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-979">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-980">署名/検証アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="bf282-980">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="bf282-981">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-981">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="bf282-982">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="bf282-982">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-983">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-983">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-984">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-984">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-985">指定したキーを使用してダイジェストをから署名を作成します。</span><span class="sxs-lookup"><span data-stu-id="bf282-985">Creates a signature from a digest using the specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-986">サインイン操作は、非対称キーおよび対称キーをこの操作は、キーの秘密部分を使用するために、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-986">The SIGN operation is applicable to asymmetric and symmetric keys stored in Azure Key Vault since this operation uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-987">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-987">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-988">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-988">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-989">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-989">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-990">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-990">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-991">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-991">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.UnwrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UnwrapKeyWithHttpMessagesAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-992">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-992">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-993">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-993">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-994">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-994">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-995">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="bf282-995">algorithm identifier.</span></span> <span data-ttu-id="bf282-996">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="bf282-996">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-997">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-997">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-998">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-998">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-999">そのキーをラップするために使用された最初に指定したキーを使用して対称キーのラップを解除します。</span><span class="sxs-lookup"><span data-stu-id="bf282-999">Unwraps a symmetric key using the specified key that was initially used for wrapping that key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1000">UNWRAP 操作は、対象キーの暗号化キーを使用して対称キーの復号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-1000">The UNWRAP operation supports decryption of a symmetric key using the target key encryption key.</span></span> <span data-ttu-id="bf282-1001">この操作は、WRAP 操作の逆です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1001">This operation is the reverse of the WRAP operation.</span></span> <span data-ttu-id="bf282-1002">UNWRAP 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1002">The UNWRAP operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1003">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1003">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1004">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1004">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1005">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1005">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1006">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1006">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1007">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1007">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateIssuerWithHttpMessagesAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1008">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1008">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="bf282-1009">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1009">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="bf282-1010">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="bf282-1010">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="bf282-1011">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="bf282-1011">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="bf282-1012">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1012">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="bf282-1013">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-1013">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1014">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1014">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1015">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1015">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1016">指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1016">Updates the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1017">UpdateCertificateIssuer 操作は、指定された証明書発行者のエンティティの更新プログラムを実行します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1017">The UpdateCertificateIssuer operation performs an update on the specified certificate issuer entity.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1018">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1018">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1019">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1019">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1020">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1020">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1021">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1021">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1022">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1022">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, bool cancellationRequested, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, cancellationRequested, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateOperationWithHttpMessagesAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1023">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1023">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-1024">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1024">The name of the certificate.</span></span>
            </param>
        <param name="cancellationRequested">
            <span data-ttu-id="bf282-1025">証明書の操作のキャンセルが要求されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1025">Indicates if cancellation was requested on the certificate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1026">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1026">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1027">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1027">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1028">証明書の操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1028">Updates a certificate operation.</span></span> <span data-ttu-id="bf282-1029">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1029">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1030">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1030">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1031">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1031">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1032">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1032">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1033">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1033">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1034">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1034">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificatePolicyWithHttpMessagesAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1035">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1035">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-1036">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1036">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="bf282-1037">証明書のポリシーです。</span><span class="sxs-lookup"><span data-stu-id="bf282-1037">The policy for the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1038">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1038">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1039">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1039">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1040">証明書のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1040">Updates the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1041">証明書のポリシーで指定したメンバーを設定します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1041">Set specified members in the certificate policy.</span></span> <span data-ttu-id="bf282-1042">Null として他のユーザーのままにします。</span><span class="sxs-lookup"><span data-stu-id="bf282-1042">Leave others as null.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1043">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1043">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1044">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1044">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1045">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1045">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1046">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1046">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1047">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1047">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateWithHttpMessagesAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1048">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1048">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="bf282-1049">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1049">The name of the certificate in the given key vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="bf282-1050">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1050">The version of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="bf282-1051">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="bf282-1051">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="bf282-1052">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-1052">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-1053">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-1053">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1054">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1054">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1055">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1055">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1056">特定の証明書に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1056">Updates the specified attributes associated with the given certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1057">UpdateCertificate 操作は指定された証明書の指定した更新プログラムを適用します。要素だけが更新中は、証明書の属性に注意してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-1057">The UpdateCertificate operation applies the specified update on the given certificate; note the only elements being updated are the certificate's attributes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1058">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1058">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1059">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1059">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1060">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1060">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1061">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1061">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1062">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1062">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.UpdateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateKeyWithHttpMessagesAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1063">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1063">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-1064">更新するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1064">The name of key to update.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-1065">更新するキーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1065">The version of the key to update.</span></span>
            </param>
        <param name="keyOps">
            <span data-ttu-id="bf282-1066">Json web キー操作。</span><span class="sxs-lookup"><span data-stu-id="bf282-1066">Json web key operations.</span></span> <span data-ttu-id="bf282-1067">考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-1067">For more information on possible key operations, see JsonWebKeyOperation.</span></span>
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="bf282-1068">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-1068">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1069">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1069">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1070">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1070">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1071">キー操作の変更の更新は、格納されたキーの属性を指定し、任意のキーの型と Azure Key Vault に格納されているキーのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1071">The update key operation changes specified attributes of a stored key and can be applied to any key type and key version stored in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1072">この操作を実行するために Key Vault にキーが既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="bf282-1072">In order to perform this operation, the key must already exist in the Key Vault.</span></span> <span data-ttu-id="bf282-1073">注: キー自体の暗号化マテリアルは変更できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-1073">Note: The cryptographic material of a key itself cannot be changed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1074">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1074">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1075">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1075">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1076">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1076">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1077">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1077">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1078">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1078">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSasDefinitionWithHttpMessagesAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1079">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1079">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-1080">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1080">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="bf282-1081">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1081">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bf282-1082">Sas の定義は、キー/値ペアの形式でメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1082">Sas definition update metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="bf282-1083">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1083">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-1084">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-1084">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1085">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1085">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1086">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1086">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1087">特定の SAS 定義に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1087">Updates the specified attributes associated with the given SAS definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1088">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1088">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1089">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1089">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1090">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1090">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1091">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1091">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1092">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1092">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.UpdateSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSecretWithHttpMessagesAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1093">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1093">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="bf282-1094">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1094">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="bf282-1095">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1095">The version of the secret.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="bf282-1096">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="bf282-1096">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="bf282-1097">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1097">The secret management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-1098">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-1098">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1099">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1099">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1100">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1100">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1101">指定されたキー コンテナーに指定されたシークレットを使用して関連付けられている属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1101">Updates the attributes associated with a specified secret in a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1102">更新操作は、既存の格納されているシークレットの指定された属性を変更します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1102">The UPDATE operation changes specified attributes of an existing stored secret.</span></span> <span data-ttu-id="bf282-1103">要求で指定されていない属性のまま変更されません。</span><span class="sxs-lookup"><span data-stu-id="bf282-1103">Attributes that are not specified in the request are left unchanged.</span></span> <span data-ttu-id="bf282-1104">シークレット自体の値は変更できません。</span><span class="sxs-lookup"><span data-stu-id="bf282-1104">The value of a secret itself cannot be changed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1105">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1105">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1106">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1106">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1107">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1107">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1108">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1109">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1109">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.UpdateStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateStorageAccountWithHttpMessagesAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1110">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1110">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="bf282-1111">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bf282-1111">The name of the storage account.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="bf282-1112">現在アクティブなストレージ アカウント キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-1112">The current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="bf282-1113">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf282-1113">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="bf282-1114">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="bf282-1114">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="bf282-1115">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="bf282-1115">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="bf282-1116">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="bf282-1116">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1117">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1119">特定のストレージ アカウントに関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1119">Updates the specified attributes associated with the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1122">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1123">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1124">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1124">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;&#xA;override this.VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;" Usage="keyVaultClient.VerifyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;VerifyWithHttpMessagesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1125">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1125">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-1126">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-1126">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-1127">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1127">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-1128">署名/検証アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="bf282-1128">The signing/verification algorithm.</span></span> <span data-ttu-id="bf282-1129">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bf282-1129">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="bf282-1130">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="bf282-1130">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="digest">
            <span data-ttu-id="bf282-1131">ダイジェストの署名に使用します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1131">The digest used for signing.</span></span>
            </param>
        <param name="signature">
            <span data-ttu-id="bf282-1132">検証対象の署名。</span><span class="sxs-lookup"><span data-stu-id="bf282-1132">The signature to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1133">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1135">指定したキーを使用して署名を確認します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1135">Verifies a signature using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1136">検証処理は、Azure Key Vault に格納された対称キーを適用されます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1136">The VERIFY operation is applicable to symmetric keys stored in Azure Key Vault.</span></span> <span data-ttu-id="bf282-1137">確認は不要な厳密にキーのパブリック部分を使用して署名の検証を実行できますが、この操作は、キー参照のみを持つ呼び出し元の便宜を図ってサポートので、Azure Key Vault に格納されている非対称キーのないと、キーのパブリックの部分です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1137">VERIFY is not strictly necessary for asymmetric keys stored in Azure Key Vault since signature verification can be performed using the public portion of the key but this operation is supported as a convenience for callers that only have a key-reference and not the public portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1140">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1141">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1142">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1142">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.WrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;WrapKeyWithHttpMessagesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="bf282-1143">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1143">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="bf282-1144">キー名。</span><span class="sxs-lookup"><span data-stu-id="bf282-1144">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="bf282-1145">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1145">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="bf282-1146">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="bf282-1146">algorithm identifier.</span></span> <span data-ttu-id="bf282-1147">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="bf282-1147">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="bf282-1148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf282-1148">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf282-1149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf282-1149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf282-1150">指定したキーを使用して対称キーをラップします。</span><span class="sxs-lookup"><span data-stu-id="bf282-1150">Wraps a symmetric key using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf282-1151">WRAP 操作では、以前、Azure Key Vault に格納されているキーの暗号化キーを使用して対称キーの暗号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="bf282-1151">The WRAP operation supports encryption of a symmetric key using a key encryption key that has previously been stored in an Azure Key Vault.</span></span> <span data-ttu-id="bf282-1152">WRAP 操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="bf282-1152">The WRAP operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using the public portion of the key.</span></span> <span data-ttu-id="bf282-1153">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="bf282-1153">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="bf282-1154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf282-1155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf282-1156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1156">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="bf282-1157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf282-1157">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="bf282-1158">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bf282-1158">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
  </Members>
</Type>