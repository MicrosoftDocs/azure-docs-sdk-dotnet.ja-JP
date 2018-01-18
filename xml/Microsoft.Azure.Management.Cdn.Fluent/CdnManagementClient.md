<Type Name="CdnManagementClient" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient">
  <TypeSignature Language="C#" Value="public class CdnManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CdnManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient&gt; implements class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CdnManagementClient&#xA;Inherits ServiceClient(Of CdnManagementClient)&#xA;Implements IAzureClient, ICdnManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type CdnManagementClient = class&#xA;    inherit ServiceClient&lt;CdnManagementClient&gt;&#xA;    interface ICdnManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient</InterfaceName>
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
            <span data-ttu-id="11d62-101">これらの Api を使用すると、Azure リソース マネージャーを通して Azure CDN のリソースを管理できます。</span><span class="sxs-lookup"><span data-stu-id="11d62-101">Use these APIs to manage Azure CDN resources through the Azure Resource Manager.</span></span> <span data-ttu-id="11d62-102">これらのリソースへの要求が安全であることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="11d62-102">You must make sure that requests made to these resources are secure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CdnManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-103">Optional.</span></span> <span data-ttu-id="11d62-104">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-104">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-105">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-105">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CdnManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-106">必須。</span><span class="sxs-lookup"><span data-stu-id="11d62-106">Required.</span></span> <span data-ttu-id="11d62-107">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="11d62-107">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-108">Optional.</span></span> <span data-ttu-id="11d62-109">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-109">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-110">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-110">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CdnManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-112">Optional.</span></span> <span data-ttu-id="11d62-113">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-113">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-114">Optional.</span></span> <span data-ttu-id="11d62-115">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-115">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-116">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-116">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CdnManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-117">Optional.</span></span> <span data-ttu-id="11d62-118">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="11d62-118">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-119">Optional.</span></span> <span data-ttu-id="11d62-120">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-120">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-121">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-121">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CdnManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-123">必須。</span><span class="sxs-lookup"><span data-stu-id="11d62-123">Required.</span></span> <span data-ttu-id="11d62-124">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="11d62-124">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="11d62-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-125">Optional.</span></span> <span data-ttu-id="11d62-126">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-126">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-127">Optional.</span></span> <span data-ttu-id="11d62-128">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-128">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-129">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-129">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CdnManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-131">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-131">Optional.</span></span> <span data-ttu-id="11d62-132">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="11d62-132">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="11d62-133">必須。</span><span class="sxs-lookup"><span data-stu-id="11d62-133">Required.</span></span> <span data-ttu-id="11d62-134">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="11d62-134">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-135">Optional.</span></span> <span data-ttu-id="11d62-136">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-136">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-137">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-137">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CdnManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-139">Optional.</span></span> <span data-ttu-id="11d62-140">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="11d62-140">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="11d62-141">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-141">Optional.</span></span> <span data-ttu-id="11d62-142">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-142">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-143">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-143">Optional.</span></span> <span data-ttu-id="11d62-144">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-144">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-145">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-145">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CdnManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="11d62-147">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-147">Optional.</span></span> <span data-ttu-id="11d62-148">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="11d62-148">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="11d62-149">必須。</span><span class="sxs-lookup"><span data-stu-id="11d62-149">Required.</span></span> <span data-ttu-id="11d62-150">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="11d62-150">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="11d62-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-151">Optional.</span></span> <span data-ttu-id="11d62-152">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-152">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="11d62-153">省略可能。</span><span class="sxs-lookup"><span data-stu-id="11d62-153">Optional.</span></span> <span data-ttu-id="11d62-154">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="11d62-154">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-155">CdnManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11d62-155">Initializes a new instance of the CdnManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-157">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="11d62-157">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-158">クライアント要求で使用する API のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="11d62-158">Version of the API to be used with the client request.</span></span> <span data-ttu-id="11d62-159">現在のバージョンは、2016-10-02 です。</span><span class="sxs-lookup"><span data-stu-id="11d62-159">Current version is 2016-10-02.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-160">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="11d62-160">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt;&#xA;override this.CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt;" Usage="cdnManagementClient.CheckNameAvailabilityWithHttpMessagesAsync (name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient/&lt;CheckNameAvailabilityWithHttpMessagesAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="11d62-161">検証対象のリソース名。</span><span class="sxs-lookup"><span data-stu-id="11d62-161">The resource name to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="11d62-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11d62-162">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11d62-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11d62-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-164">リソース名の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="11d62-164">Check the availability of a resource name.</span></span> <span data-ttu-id="11d62-165">CDN エンドポイントなど、グローバルに一意な名前のリソースに必要です。</span><span class="sxs-lookup"><span data-stu-id="11d62-165">This is needed for resources where name is globally unique, such as a CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="11d62-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="11d62-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11d62-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-168">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-169">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="11d62-170">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="11d62-170">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-171">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="11d62-171">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations CustomDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations CustomDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.CustomDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomains As ICustomDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.CustomDomains : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.CustomDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-172">ICustomDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="11d62-172">Gets the ICustomDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-173">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="11d62-173">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations EdgeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations EdgeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.EdgeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EdgeNodes As IEdgeNodesOperations" />
      <MemberSignature Language="F#" Value="member this.EdgeNodes : Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.EdgeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-174">IEdgeNodesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="11d62-174">Gets the IEdgeNodesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As IEndpointsOperations" />
      <MemberSignature Language="F#" Value="member this.Endpoints : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-175">IEndpointsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="11d62-175">Gets the IEndpointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-176">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="11d62-176">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="11d62-177">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="11d62-177">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ListOperationsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOperationsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;&#xA;override this.ListOperationsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;" Usage="cdnManagementClient.ListOperationsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListOperationsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient/&lt;ListOperationsNextWithHttpMessagesAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="11d62-178">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="11d62-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="11d62-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11d62-179">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11d62-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11d62-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-181">すべての利用可能な CDN の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="11d62-181">Lists all of the available CDN REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="11d62-182">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-182">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="11d62-183">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-183">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11d62-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-184">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-185">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="11d62-186">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="11d62-186">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ListOperationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOperationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;&#xA;override this.ListOperationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;" Usage="cdnManagementClient.ListOperationsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListOperationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient/&lt;ListOperationsWithHttpMessagesAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="11d62-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11d62-187">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11d62-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11d62-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-189">すべての利用可能な CDN の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="11d62-189">Lists all of the available CDN REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="11d62-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="11d62-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11d62-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-192">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-193">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-193">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="11d62-194">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="11d62-194">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ListResourceUsageNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;&#xA;override this.ListResourceUsageNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="cdnManagementClient.ListResourceUsageNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListResourceUsageNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient/&lt;ListResourceUsageNextWithHttpMessagesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="11d62-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="11d62-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="11d62-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11d62-196">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11d62-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11d62-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-198">クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。</span><span class="sxs-lookup"><span data-stu-id="11d62-198">Check the quota and actual usage of the CDN profiles under the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="11d62-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="11d62-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11d62-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-201">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-202">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="11d62-203">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="11d62-203">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.ListResourceUsageWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;&#xA;override this.ListResourceUsageWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="cdnManagementClient.ListResourceUsageWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListResourceUsageWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient/&lt;ListResourceUsageWithHttpMessagesAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="11d62-204">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11d62-204">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11d62-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11d62-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11d62-206">クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。</span><span class="sxs-lookup"><span data-stu-id="11d62-206">Check the quota and actual usage of the CDN profiles under the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="11d62-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="11d62-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11d62-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-209">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="11d62-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11d62-210">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="11d62-211">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="11d62-211">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-212">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="11d62-212">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="11d62-213">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="11d62-213">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origins">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations Origins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations Origins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Origins" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origins As IOriginsOperations" />
      <MemberSignature Language="F#" Value="member this.Origins : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Origins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-214">IOriginsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="11d62-214">Gets the IOriginsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Profiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations Profiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations Profiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Profiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Profiles As IProfilesOperations" />
      <MemberSignature Language="F#" Value="member this.Profiles : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.Profiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-215">IProfilesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="11d62-215">Gets the IProfilesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-216">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="11d62-216">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11d62-217">Azure サブスクリプション ID。</span><span class="sxs-lookup"><span data-stu-id="11d62-217">Azure Subscription ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>