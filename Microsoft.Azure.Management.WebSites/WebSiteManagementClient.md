<Type Name="WebSiteManagementClient" FullName="Microsoft.Azure.Management.WebSites.WebSiteManagementClient">
  <TypeSignature Language="C#" Value="public class WebSiteManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.WebSites.WebSiteManagementClient&gt;, IDisposable, Microsoft.Azure.Management.WebSites.IWebSiteManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebSiteManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.WebSites.WebSiteManagementClient&gt; implements class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.WebSiteManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class WebSiteManagementClient&#xA;Inherits ServiceClient(Of WebSiteManagementClient)&#xA;Implements IAzureClient, IDisposable, IWebSiteManagementClient" />
  <TypeSignature Language="F#" Value="type WebSiteManagementClient = class&#xA;    inherit ServiceClient&lt;WebSiteManagementClient&gt;&#xA;    interface IWebSiteManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.WebSites.WebSiteManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.WebSites.WebSiteManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.WebSites.IWebSiteManagementClient</InterfaceName>
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
            <span data-ttu-id="f4d82-101">Web サイト管理クライアント</span><span class="sxs-lookup"><span data-stu-id="f4d82-101">WebSite Management Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WebSiteManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f4d82-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-102">Optional.</span></span> <span data-ttu-id="f4d82-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-104">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-104">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebSiteManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f4d82-105">必須。</span><span class="sxs-lookup"><span data-stu-id="f4d82-105">Required.</span></span> <span data-ttu-id="f4d82-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-107">Optional.</span></span> <span data-ttu-id="f4d82-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-109">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-109">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WebSiteManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f4d82-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-111">Optional.</span></span> <span data-ttu-id="f4d82-112">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-113">Optional.</span></span> <span data-ttu-id="f4d82-114">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-115">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-115">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WebSiteManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="f4d82-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-116">Optional.</span></span> <span data-ttu-id="f4d82-117">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f4d82-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-118">Optional.</span></span> <span data-ttu-id="f4d82-119">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-120">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-120">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebSiteManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f4d82-122">必須。</span><span class="sxs-lookup"><span data-stu-id="f4d82-122">Required.</span></span> <span data-ttu-id="f4d82-123">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f4d82-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-124">Optional.</span></span> <span data-ttu-id="f4d82-125">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-126">Optional.</span></span> <span data-ttu-id="f4d82-127">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-128">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-128">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebSiteManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            <span data-ttu-id="f4d82-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-130">Optional.</span></span> <span data-ttu-id="f4d82-131">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f4d82-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f4d82-132">必須。</span><span class="sxs-lookup"><span data-stu-id="f4d82-132">Required.</span></span> <span data-ttu-id="f4d82-133">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-134">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-134">Optional.</span></span> <span data-ttu-id="f4d82-135">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-136">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-136">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WebSiteManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            <span data-ttu-id="f4d82-138">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-138">Optional.</span></span> <span data-ttu-id="f4d82-139">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f4d82-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f4d82-140">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-140">Optional.</span></span> <span data-ttu-id="f4d82-141">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-142">Optional.</span></span> <span data-ttu-id="f4d82-143">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-144">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-144">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebSiteManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.WebSites.WebSiteManagementClient" Usage="new Microsoft.Azure.Management.WebSites.WebSiteManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            <span data-ttu-id="f4d82-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-146">Optional.</span></span> <span data-ttu-id="f4d82-147">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f4d82-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f4d82-148">必須。</span><span class="sxs-lookup"><span data-stu-id="f4d82-148">Required.</span></span> <span data-ttu-id="f4d82-149">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f4d82-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-150">Optional.</span></span> <span data-ttu-id="f4d82-151">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4d82-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f4d82-152">Optional.</span></span> <span data-ttu-id="f4d82-153">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f4d82-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-154">WebSiteManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-154">Initializes a new instance of the WebSiteManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-156">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateOrders">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateOrders As IAppServiceCertificateOrdersOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateOrders : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-157">IAppServiceCertificateOrdersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-157">Gets the IAppServiceCertificateOrdersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServiceEnvironments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceEnvironments As IAppServiceEnvironmentsOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironments : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServiceEnvironments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-158">IAppServiceEnvironmentsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-158">Gets the IAppServiceEnvironmentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlans">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServicePlans" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServicePlans As IAppServicePlansOperations" />
      <MemberSignature Language="F#" Value="member this.AppServicePlans : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.AppServicePlans" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServicePlansOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-159">IAppServicePlansOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-159">Gets the IAppServicePlansOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-160">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f4d82-160">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificates As ICertificatesOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.WebSites.ICertificatesOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ICertificatesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-161">ICertificatesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-161">Gets the ICertificatesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;&#xA;override this.CheckNameAvailabilityWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;" Usage="webSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync (name, type, isFqdn, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;CheckNameAvailabilityWithHttpMessagesAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="f4d82-162">リソース名を確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4d82-162">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="f4d82-163">リソースの種類の検証に使用します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-163">Resource type used for verification.</span></span> <span data-ttu-id="f4d82-164">使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'</span><span class="sxs-lookup"><span data-stu-id="f4d82-164">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="f4d82-165">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-165">Is fully qualified domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-166">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-168">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-168">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-169">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-169">Check if a resource name is available.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-172">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-173">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-174">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-174">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-175">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-175">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedWebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.DeletedWebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedWebApps As IDeletedWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.DeletedWebApps : Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.DeletedWebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-176">IDeletedWebAppsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-176">Gets the IDeletedWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-177">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-177">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDomainsOperations Domains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDomainsOperations Domains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Domains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Domains As IDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.Domains : Microsoft.Azure.Management.WebSites.IDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Domains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-178">IDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-178">Gets the IDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-179">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-179">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="f4d82-180">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-180">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingUserWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;&#xA;override this.GetPublishingUserWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="webSiteManagementClient.GetPublishingUserWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;GetPublishingUserWithHttpMessagesAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-181">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-183">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="f4d82-183">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-184">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="f4d82-184">Gets publishing user</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-186">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-186">Thrown when unable to deserialize the response</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-187">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-187">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync (string sourceControlType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync(string sourceControlType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.GetSourceControlWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControlWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&#xA;override this.GetSourceControlWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="webSiteManagementClient.GetSourceControlWithHttpMessagesAsync (sourceControlType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSourceControlWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;GetSourceControlWithHttpMessagesAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="f4d82-188">ソース管理の種類</span><span class="sxs-lookup"><span data-stu-id="f4d82-188">Type of source control</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-189">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-191">ソース管理のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-191">Gets source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-192">ソース管理のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-192">Gets source control token</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-195">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-196">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-197">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-197">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSubscriptionDeploymentLocationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;&#xA;override this.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;" Usage="webSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;GetSubscriptionDeploymentLocationsWithHttpMessagesAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-198">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-200">使用可能な地理的位置 plus ministamps の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-200">Gets list of available geo regions plus ministamps</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-201">使用可能な地理的位置 plus ministamps の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-201">Gets list of available geo regions plus ministamps</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-202">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-202">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-203">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-203">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-204">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-204">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-205">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-206">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-206">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;&#xA;override this.ListGeoRegionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="webSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListGeoRegionsNextWithHttpMessagesAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4d82-207">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-207">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-208">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-210">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-210">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-211">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-211">Get a list of available geographical regions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-214">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-215">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-215">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-216">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-216">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync (string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync(string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;&#xA;override this.ListGeoRegionsWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="webSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync (sku, linuxWorkersEnabled, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListGeoRegionsWithHttpMessagesAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sku">
            <span data-ttu-id="f4d82-217">SKU の名前は、領域をフィルター処理に使用します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-217">Name of SKU used to filter the regions.</span></span> <span data-ttu-id="f4d82-218">使用可能な値が含まれます: 'Free'、'Shared'、'Basic'、'Standard'、'Premium'、'PremiumV2'、'Dynamic'、'Isolated'</span><span class="sxs-lookup"><span data-stu-id="f4d82-218">Possible values include: 'Free', 'Shared', 'Basic', 'Standard', 'Premium', 'PremiumV2', 'Dynamic', 'Isolated'</span></span>
            </param>
        <param name="linuxWorkersEnabled">
            <span data-ttu-id="f4d82-219">指定&lt;コード&gt;true&lt;/code&gt; Linux ワーカーをサポートする領域だけにフィルターを適用する場合。</span><span class="sxs-lookup"><span data-stu-id="f4d82-219">Specify &lt;code&gt;true&lt;/code&gt; if you want to filter to only regions that support Linux workers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-220">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-220">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-222">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-222">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-223">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-223">Get a list of available geographical regions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-224">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-224">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-225">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-225">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-226">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-226">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-227">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-228">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-228">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;&#xA;override this.ListPremierAddOnOffersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="webSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListPremierAddOnOffersNextWithHttpMessagesAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4d82-229">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-229">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-230">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-232">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-232">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-233">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-233">List all premier add-on offers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-236">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-237">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-237">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-238">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-238">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;&#xA;override this.ListPremierAddOnOffersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="webSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListPremierAddOnOffersWithHttpMessagesAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-239">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-239">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-241">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-241">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-242">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-242">List all premier add-on offers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-243">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-243">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-244">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-244">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-245">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-246">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-246">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-247">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-247">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListSkusWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSkusWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;&#xA;override this.ListSkusWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;" Usage="webSiteManagementClient.ListSkusWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSkusWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListSkusWithHttpMessagesAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-248">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-248">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-250">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-250">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-251">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-251">List all SKUs.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-252">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-252">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-253">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-253">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-254">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-254">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-255">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-255">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-256">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-256">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;&#xA;override this.ListSourceControlsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="webSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListSourceControlsNextWithHttpMessagesAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4d82-257">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-258">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-258">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-260">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-260">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-261">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-261">Gets the source controls available for Azure websites.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-262">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-262">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-263">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-263">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-264">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-264">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-265">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-265">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-266">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-266">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;&#xA;override this.ListSourceControlsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="webSiteManagementClient.ListSourceControlsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ListSourceControlsWithHttpMessagesAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-267">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-267">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-268">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-268">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-269">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-269">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-270">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-270">Gets the source controls available for Azure websites.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-271">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-271">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-272">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-272">Thrown when unable to deserialize the response</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-273">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-273">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-274">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-274">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="f4d82-275">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-275">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.MoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.MoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="webSiteManagementClient.MoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.MoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;MoveWithHttpMessagesAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f4d82-276">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-276">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="f4d82-277">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-277">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-278">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-278">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-279">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-279">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-280">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-280">Move resources between resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-281">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-281">Move resources between resource groups.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-282">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-282">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-283">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-283">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-284">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-284">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-285">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-285">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IProviderOperations Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IProviderOperations Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IProviderOperations" />
      <MemberSignature Language="F#" Value="member this.Provider : Microsoft.Azure.Management.WebSites.IProviderOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IProviderOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-286">IProviderOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-286">Gets the IProviderOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recommendations As IRecommendationsOperations" />
      <MemberSignature Language="F#" Value="member this.Recommendations : Microsoft.Azure.Management.WebSites.IRecommendationsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IRecommendationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-287">IRecommendationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-287">Gets the IRecommendationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-288">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-288">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-289">Azure サブスクリプションの id。</span><span class="sxs-lookup"><span data-stu-id="f4d82-289">Your Azure subscription ID.</span></span> <span data-ttu-id="f4d82-290">これは、GUID 形式の文字列 (例: 00000000-0000-0000-0000-000000000000) です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-290">This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopLevelDomains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.TopLevelDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopLevelDomains As ITopLevelDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.TopLevelDomains : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.TopLevelDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-291">ITopLevelDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-291">Gets the ITopLevelDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.User userDetails, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.User userDetails, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.User,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublishingUserWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.User * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;&#xA;override this.UpdatePublishingUserWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.User * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="webSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync (userDetails, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.User,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;UpdatePublishingUserWithHttpMessagesAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="userDetails">
            <span data-ttu-id="f4d82-292">発行ユーザーの詳細</span><span class="sxs-lookup"><span data-stu-id="f4d82-292">Details of publishing user</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-293">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-293">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-295">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="f4d82-295">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-296">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="f4d82-296">Updates publishing user</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-297">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-297">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-298">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-298">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-299">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-299">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-300">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-300">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-301">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-301">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync (string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync(string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSourceControlWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&#xA;override this.UpdateSourceControlWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="webSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync (sourceControlType, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;UpdateSourceControlWithHttpMessagesAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="f4d82-302">ソース管理の種類</span><span class="sxs-lookup"><span data-stu-id="f4d82-302">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="f4d82-303">ソース管理のトークンの情報</span><span class="sxs-lookup"><span data-stu-id="f4d82-303">Source control token information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-304">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-304">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-305">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-306">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="f4d82-306">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-307">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="f4d82-307">Updates source control token</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-308">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-308">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-309">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-309">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-310">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-310">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-311">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-311">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-312">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-312">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ValidateMoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateMoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.ValidateMoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="webSiteManagementClient.ValidateMoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateMoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ValidateMoveWithHttpMessagesAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f4d82-313">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-313">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="f4d82-314">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-314">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-315">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-315">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-317">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-317">Validate whether a resource can be moved.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-318">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-318">Validate whether a resource can be moved.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-319">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-319">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-320">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-320">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-321">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-321">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-322">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-322">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ValidateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.ValidateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;&#xA;override this.ValidateWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;" Usage="webSiteManagementClient.ValidateWithHttpMessagesAsync (resourceGroupName, validateRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;ValidateWithHttpMessagesAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f4d82-323">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-323">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="f4d82-324">検証する、リソースを持つ要求です。</span><span class="sxs-lookup"><span data-stu-id="f4d82-324">Request with the resources to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-325">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-325">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-327">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-327">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-328">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-328">Validate if a resource can be created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-329">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-329">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-330">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-330">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-331">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-331">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-332">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-332">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-333">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-333">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyHostingEnvironmentVnetWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;&#xA;override this.VerifyHostingEnvironmentVnetWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;" Usage="webSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClient/&lt;VerifyHostingEnvironmentVnetWithHttpMessagesAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f4d82-334">VNET について</span><span class="sxs-lookup"><span data-stu-id="f4d82-334">VNET information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4d82-335">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-335">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4d82-336">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4d82-336">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4d82-337">ネットワーク セキュリティ グループ ルールを分析して、この VNET が App Service 環境に互換性があることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-337">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4d82-338">ネットワーク セキュリティ グループ ルールを分析して、この VNET が App Service 環境に互換性があることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-338">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f4d82-339">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-339">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4d82-340">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-340">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4d82-341">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-341">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4d82-342">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4d82-342">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4d82-343">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4d82-343">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="WebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.WebSiteManagementClient.WebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebApps As IWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.WebApps : Microsoft.Azure.Management.WebSites.IWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClient.WebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4d82-344">IWebAppsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4d82-344">Gets the IWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>