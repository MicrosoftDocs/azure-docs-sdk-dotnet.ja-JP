<Type Name="StorSimple8000SeriesManagementClient" FullName="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient">
  <TypeSignature Language="C#" Value="public class StorSimple8000SeriesManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient&gt;, IDisposable, Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorSimple8000SeriesManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient&gt; implements class Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class StorSimple8000SeriesManagementClient&#xA;Inherits ServiceClient(Of StorSimple8000SeriesManagementClient)&#xA;Implements IAzureClient, IDisposable, IStorSimple8000SeriesManagementClient" />
  <TypeSignature Language="F#" Value="type StorSimple8000SeriesManagementClient = class&#xA;    inherit ServiceClient&lt;StorSimple8000SeriesManagementClient&gt;&#xA;    interface IStorSimple8000SeriesManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorSimple8000SeriesManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-101">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-101">Optional.</span></span> <span data-ttu-id="35314-102">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-102">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-103">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-103">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimple8000SeriesManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-104">必須。</span><span class="sxs-lookup"><span data-stu-id="35314-104">Required.</span></span> <span data-ttu-id="35314-105">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="35314-105">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-106">Optional.</span></span> <span data-ttu-id="35314-107">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-107">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-108">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-108">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorSimple8000SeriesManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-110">Optional.</span></span> <span data-ttu-id="35314-111">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-111">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-112">Optional.</span></span> <span data-ttu-id="35314-113">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-113">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-114">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-114">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorSimple8000SeriesManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-115">Optional.</span></span> <span data-ttu-id="35314-116">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="35314-116">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-117">Optional.</span></span> <span data-ttu-id="35314-118">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-118">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-119">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-119">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimple8000SeriesManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-121">必須。</span><span class="sxs-lookup"><span data-stu-id="35314-121">Required.</span></span> <span data-ttu-id="35314-122">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="35314-122">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="35314-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-123">Optional.</span></span> <span data-ttu-id="35314-124">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-124">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-125">Optional.</span></span> <span data-ttu-id="35314-126">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-126">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-127">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-127">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimple8000SeriesManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-129">Optional.</span></span> <span data-ttu-id="35314-130">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="35314-130">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="35314-131">必須。</span><span class="sxs-lookup"><span data-stu-id="35314-131">Required.</span></span> <span data-ttu-id="35314-132">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="35314-132">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-133">Optional.</span></span> <span data-ttu-id="35314-134">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-134">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-135">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-135">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorSimple8000SeriesManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-137">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-137">Optional.</span></span> <span data-ttu-id="35314-138">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="35314-138">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="35314-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-139">Optional.</span></span> <span data-ttu-id="35314-140">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-140">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-141">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-141">Optional.</span></span> <span data-ttu-id="35314-142">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-142">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-143">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-143">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimple8000SeriesManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient" Usage="new Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="35314-145">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-145">Optional.</span></span> <span data-ttu-id="35314-146">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="35314-146">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="35314-147">必須。</span><span class="sxs-lookup"><span data-stu-id="35314-147">Required.</span></span> <span data-ttu-id="35314-148">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="35314-148">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="35314-149">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-149">Optional.</span></span> <span data-ttu-id="35314-150">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-150">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="35314-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="35314-151">Optional.</span></span> <span data-ttu-id="35314-152">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="35314-152">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35314-153">StorSimple8000SeriesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35314-153">Initializes a new instance of the StorSimple8000SeriesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="35314-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35314-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-155">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="35314-155">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessControlRecords">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations AccessControlRecords { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations AccessControlRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.AccessControlRecords" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessControlRecords As IAccessControlRecordsOperations" />
      <MemberSignature Language="F#" Value="member this.AccessControlRecords : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.AccessControlRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-156">IAccessControlRecordsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-156">Gets the IAccessControlRecordsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alerts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations Alerts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations Alerts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Alerts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Alerts As IAlertsOperations" />
      <MemberSignature Language="F#" Value="member this.Alerts : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Alerts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-157">IAlertsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-157">Gets the IAlertsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-158">Api のバージョン</span><span class="sxs-lookup"><span data-stu-id="35314-158">The api version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations BackupPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations BackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupPolicies As IBackupPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupPolicies : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-159">IBackupPoliciesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-159">Gets the IBackupPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations Backups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations Backups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Backups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backups As IBackupsOperations" />
      <MemberSignature Language="F#" Value="member this.Backups : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Backups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-160">IBackupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-160">Gets the IBackupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations BackupSchedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations BackupSchedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BackupSchedules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupSchedules As IBackupSchedulesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupSchedules : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BackupSchedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-161">IBackupSchedulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-161">Gets the IBackupSchedulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandwidthSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations BandwidthSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations BandwidthSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BandwidthSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BandwidthSettings As IBandwidthSettingsOperations" />
      <MemberSignature Language="F#" Value="member this.BandwidthSettings : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BandwidthSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-162">IBandwidthSettingsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-162">Gets the IBandwidthSettingsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-163">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="35314-163">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudAppliances">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations CloudAppliances { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations CloudAppliances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.CloudAppliances" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloudAppliances As ICloudAppliancesOperations" />
      <MemberSignature Language="F#" Value="member this.CloudAppliances : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.CloudAppliances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-164">ICloudAppliancesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-164">Gets the ICloudAppliancesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-165">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="35314-165">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-166">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="35314-166">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Devices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations Devices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations Devices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Devices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Devices As IDevicesOperations" />
      <MemberSignature Language="F#" Value="member this.Devices : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Devices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-167">IDevicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-167">Gets the IDevicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations DeviceSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations DeviceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.DeviceSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceSettings As IDeviceSettingsOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.DeviceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-168">IDeviceSettingsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-168">Gets the IDeviceSettingsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-169">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="35314-169">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="35314-170">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="35314-170">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareComponentGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations HardwareComponentGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations HardwareComponentGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.HardwareComponentGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HardwareComponentGroups As IHardwareComponentGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.HardwareComponentGroups : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.HardwareComponentGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-171">IHardwareComponentGroupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-171">Gets the IHardwareComponentGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Jobs As IJobsOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Jobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-172">IJobsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-172">Gets the IJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-173">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="35314-173">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="35314-174">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="35314-174">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Managers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations Managers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations Managers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Managers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Managers As IManagersOperations" />
      <MemberSignature Language="F#" Value="member this.Managers : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Managers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-175">IManagersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-175">Gets the IManagersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.StorSimple8000Series.IOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-176">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-176">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-177">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="35314-177">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations StorageAccountCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations StorageAccountCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.StorageAccountCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountCredentials As IStorageAccountCredentialsOperations" />
      <MemberSignature Language="F#" Value="member this.StorageAccountCredentials : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.StorageAccountCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-178">IStorageAccountCredentialsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-178">Gets the IStorageAccountCredentialsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.StorSimple8000Series.IStorSimple8000SeriesManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-179">サブスクリプション id</span><span class="sxs-lookup"><span data-stu-id="35314-179">The subscription id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations VolumeContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations VolumeContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.VolumeContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VolumeContainers As IVolumeContainersOperations" />
      <MemberSignature Language="F#" Value="member this.VolumeContainers : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.VolumeContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-180">IVolumeContainersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-180">Gets the IVolumeContainersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations Volumes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Volumes As IVolumesOperations" />
      <MemberSignature Language="F#" Value="member this.Volumes : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorSimple8000SeriesManagementClient.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35314-181">IVolumesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="35314-181">Gets the IVolumesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>