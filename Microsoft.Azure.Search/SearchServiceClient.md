<Type Name="SearchServiceClient" FullName="Microsoft.Azure.Search.SearchServiceClient">
  <TypeSignature Language="C#" Value="public class SearchServiceClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Search.SearchServiceClient&gt;, IDisposable, Microsoft.Azure.Search.ISearchServiceClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchServiceClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Search.SearchServiceClient&gt; implements class Microsoft.Azure.Search.ISearchServiceClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SearchServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchServiceClient&#xA;Inherits ServiceClient(Of SearchServiceClient)&#xA;Implements IAzureClient, IDisposable, ISearchServiceClient" />
  <TypeSignature Language="F#" Value="type SearchServiceClient = class&#xA;    inherit ServiceClient&lt;SearchServiceClient&gt;&#xA;    interface ISearchServiceClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Search.SearchServiceClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Search.SearchServiceClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.ISearchServiceClient</InterfaceName>
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
            <span data-ttu-id="2e98e-101">管理し、インデックス、およびドキュメントのクエリを実行するだけでなく Azure Search サービスで他のリソースを管理するために使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="2e98e-101">Client that can be used to manage and query indexes and documents, as well as manage other resources, on an Azure Search service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SearchServiceClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e98e-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-102">Optional.</span></span> <span data-ttu-id="2e98e-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e98e-104">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-104">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchServiceClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e98e-105">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-105">Required.</span></span> <span data-ttu-id="2e98e-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="2e98e-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-107">Optional.</span></span> <span data-ttu-id="2e98e-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e98e-109">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-109">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="2e98e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2e98e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SearchServiceClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e98e-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-111">Optional.</span></span> <span data-ttu-id="2e98e-112">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="2e98e-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-113">Optional.</span></span> <span data-ttu-id="2e98e-114">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e98e-115">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-115">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchServiceClient (string searchServiceName, Microsoft.Azure.Search.SearchCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string searchServiceName, class Microsoft.Azure.Search.SearchCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(System.String,Microsoft.Azure.Search.SearchCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (searchServiceName As String, credentials As SearchCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : string * Microsoft.Azure.Search.SearchCredentials -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient (searchServiceName, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.SearchCredentials" />
      </Parameters>
      <Docs>
        <param name="searchServiceName"><span data-ttu-id="2e98e-116">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-116">Required.</span></span> <span data-ttu-id="2e98e-117">Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="2e98e-117">The name of the Azure Search service.</span></span></param>
        <param name="credentials"><span data-ttu-id="2e98e-118">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-118">Required.</span></span> <span data-ttu-id="2e98e-119">Azure Search サービスへの認証に使用される資格情報。</span><span class="sxs-lookup"><span data-stu-id="2e98e-119">The credentials used to authenticate to an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/" /></param>
        <summary>
            <span data-ttu-id="2e98e-120">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-120">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchServiceClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e98e-121">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-121">Required.</span></span> <span data-ttu-id="2e98e-122">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-122">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="2e98e-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-123">Optional.</span></span> <span data-ttu-id="2e98e-124">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-124">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="2e98e-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-125">Optional.</span></span> <span data-ttu-id="2e98e-126">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-126">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e98e-127">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-127">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="2e98e-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2e98e-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchServiceClient (string searchServiceName, Microsoft.Azure.Search.SearchCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string searchServiceName, class Microsoft.Azure.Search.SearchCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchServiceClient.#ctor(System.String,Microsoft.Azure.Search.SearchCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (searchServiceName As String, credentials As SearchCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchServiceClient : string * Microsoft.Azure.Search.SearchCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Search.SearchServiceClient" Usage="new Microsoft.Azure.Search.SearchServiceClient (searchServiceName, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.SearchCredentials" />
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
        <param name="searchServiceName"><span data-ttu-id="2e98e-129">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-129">Required.</span></span> <span data-ttu-id="2e98e-130">Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="2e98e-130">The name of the Azure Search service.</span></span></param>
        <param name="credentials"><span data-ttu-id="2e98e-131">必須。</span><span class="sxs-lookup"><span data-stu-id="2e98e-131">Required.</span></span> <span data-ttu-id="2e98e-132">Azure Search サービスへの認証に使用される資格情報。</span><span class="sxs-lookup"><span data-stu-id="2e98e-132">The credentials used to authenticate to an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/" /></param>
        <param name="rootHandler">
            <span data-ttu-id="2e98e-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-133">Optional.</span></span> <span data-ttu-id="2e98e-134">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="2e98e-134">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="2e98e-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2e98e-135">Optional.</span></span> <span data-ttu-id="2e98e-136">Http クライアント パイプラインに挿入するハンドラーの委任のセット。</span><span class="sxs-lookup"><span data-stu-id="2e98e-136">The set of delegating handlers to insert in the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e98e-137">SearchServiceClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-137">Initializes a new instance of the SearchServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Search.SearchServiceClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-138">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-138">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Search.SearchServiceClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-139">クライアント Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="2e98e-139">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Search.SearchServiceClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-140">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-140">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IDataSourcesOperations DataSources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IDataSourcesOperations DataSources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.DataSources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSources As IDataSourcesOperations" />
      <MemberSignature Language="F#" Value="member this.DataSources : Microsoft.Azure.Search.IDataSourcesOperations" Usage="Microsoft.Azure.Search.SearchServiceClient.DataSources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IDataSourcesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-141">IDataSourcesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-141">Gets the IDataSourcesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.SearchServiceClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-142">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-142">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.SearchServiceClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-143">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="2e98e-143">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="2e98e-144">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-144">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IIndexersOperations Indexers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IIndexersOperations Indexers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.Indexers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Indexers As IIndexersOperations" />
      <MemberSignature Language="F#" Value="member this.Indexers : Microsoft.Azure.Search.IIndexersOperations" Usage="Microsoft.Azure.Search.SearchServiceClient.Indexers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IIndexersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-145">IIndexersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-145">Gets the IIndexersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IIndexesOperations Indexes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IIndexesOperations Indexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.Indexes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Indexes As IIndexesOperations" />
      <MemberSignature Language="F#" Value="member this.Indexes : Microsoft.Azure.Search.IIndexesOperations" Usage="Microsoft.Azure.Search.SearchServiceClient.Indexes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IIndexesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-146">IIndexesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-146">Gets the IIndexesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.SearchServiceClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-147">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-147">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="2e98e-148">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-148">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.SearchCredentials SearchCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.SearchCredentials SearchCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.SearchCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchCredentials As SearchCredentials" />
      <MemberSignature Language="F#" Value="member this.SearchCredentials : Microsoft.Azure.Search.SearchCredentials" Usage="Microsoft.Azure.Search.SearchServiceClient.SearchCredentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.SearchCredentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.SearchCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="SearchDnsSuffix">
      <MemberSignature Language="C#" Value="public string SearchDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.SearchDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.SearchDnsSuffix : string with get, set" Usage="Microsoft.Azure.Search.SearchServiceClient.SearchDnsSuffix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.SearchDnsSuffix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-149">Azure Search サービスの DNS サフィックス。</span><span class="sxs-lookup"><span data-stu-id="2e98e-149">The DNS suffix of the Azure Search service.</span></span> <span data-ttu-id="2e98e-150">既定値は、&lt;name&gt;.search.windows.net です。</span><span class="sxs-lookup"><span data-stu-id="2e98e-150">The default is search.windows.net.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchServiceName">
      <MemberSignature Language="C#" Value="public string SearchServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.SearchServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchServiceName As String" />
      <MemberSignature Language="F#" Value="member this.SearchServiceName : string with get, set" Usage="Microsoft.Azure.Search.SearchServiceClient.SearchServiceName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Search.ISearchServiceClient.SearchServiceName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-151">Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="2e98e-151">The name of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.SearchServiceClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-152">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-152">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynonymMaps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.ISynonymMapsOperations SynonymMaps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.ISynonymMapsOperations SynonymMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchServiceClient.SynonymMaps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SynonymMaps As ISynonymMapsOperations" />
      <MemberSignature Language="F#" Value="member this.SynonymMaps : Microsoft.Azure.Search.ISynonymMapsOperations" Usage="Microsoft.Azure.Search.SearchServiceClient.SynonymMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.ISynonymMapsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e98e-153">ISynonymMapsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e98e-153">Gets the ISynonymMapsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>