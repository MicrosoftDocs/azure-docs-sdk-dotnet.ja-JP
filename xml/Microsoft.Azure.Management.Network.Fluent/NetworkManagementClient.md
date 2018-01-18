<Type Name="NetworkManagementClient" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient">
  <TypeSignature Language="C#" Value="public class NetworkManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient&gt; implements class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkManagementClient&#xA;Inherits ServiceClient(Of NetworkManagementClient)&#xA;Implements IAzureClient, IDisposable, INetworkManagementClient" />
  <TypeSignature Language="F#" Value="type NetworkManagementClient = class&#xA;    inherit ServiceClient&lt;NetworkManagementClient&gt;&#xA;    interface INetworkManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient</InterfaceName>
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
            <span data-ttu-id="8b225-101">ネットワーク クライアントに対して複合 Swagger</span><span class="sxs-lookup"><span data-stu-id="8b225-101">Composite Swagger for Network Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetworkManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-102">Optional.</span></span> <span data-ttu-id="8b225-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-104">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-104">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-105">必須。</span><span class="sxs-lookup"><span data-stu-id="8b225-105">Required.</span></span> <span data-ttu-id="8b225-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="8b225-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-107">Optional.</span></span> <span data-ttu-id="8b225-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-109">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-109">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetworkManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-111">Optional.</span></span> <span data-ttu-id="8b225-112">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-113">Optional.</span></span> <span data-ttu-id="8b225-114">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-115">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-115">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetworkManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-116">Optional.</span></span> <span data-ttu-id="8b225-117">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="8b225-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-118">Optional.</span></span> <span data-ttu-id="8b225-119">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-120">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-120">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-122">必須。</span><span class="sxs-lookup"><span data-stu-id="8b225-122">Required.</span></span> <span data-ttu-id="8b225-123">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="8b225-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8b225-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-124">Optional.</span></span> <span data-ttu-id="8b225-125">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-126">Optional.</span></span> <span data-ttu-id="8b225-127">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-128">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-128">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-130">Optional.</span></span> <span data-ttu-id="8b225-131">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="8b225-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="8b225-132">必須。</span><span class="sxs-lookup"><span data-stu-id="8b225-132">Required.</span></span> <span data-ttu-id="8b225-133">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="8b225-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-134">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-134">Optional.</span></span> <span data-ttu-id="8b225-135">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-136">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-136">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetworkManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-138">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-138">Optional.</span></span> <span data-ttu-id="8b225-139">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="8b225-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8b225-140">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-140">Optional.</span></span> <span data-ttu-id="8b225-141">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-142">Optional.</span></span> <span data-ttu-id="8b225-143">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-144">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-144">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient" Usage="new Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="8b225-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-146">Optional.</span></span> <span data-ttu-id="8b225-147">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="8b225-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="8b225-148">必須。</span><span class="sxs-lookup"><span data-stu-id="8b225-148">Required.</span></span> <span data-ttu-id="8b225-149">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="8b225-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8b225-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-150">Optional.</span></span> <span data-ttu-id="8b225-151">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8b225-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="8b225-152">Optional.</span></span> <span data-ttu-id="8b225-153">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="8b225-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-154">NetworkManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b225-154">Initializes a new instance of the NetworkManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-156">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b225-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations ApplicationGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations ApplicationGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ApplicationGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationGateways As IApplicationGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationGateways : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ApplicationGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-157">IApplicationGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-157">Gets the IApplicationGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableEndpointServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IAvailableEndpointServicesOperations AvailableEndpointServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IAvailableEndpointServicesOperations AvailableEndpointServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.AvailableEndpointServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailableEndpointServices As IAvailableEndpointServicesOperations" />
      <MemberSignature Language="F#" Value="member this.AvailableEndpointServices : Microsoft.Azure.Management.Network.Fluent.IAvailableEndpointServicesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.AvailableEndpointServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IAvailableEndpointServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-158">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="8b225-158">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpServiceCommunities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations BgpServiceCommunities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations BgpServiceCommunities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.BgpServiceCommunities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BgpServiceCommunities As IBgpServiceCommunitiesOperations" />
      <MemberSignature Language="F#" Value="member this.BgpServiceCommunities : Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.BgpServiceCommunities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-159">IBgpServiceCommunitiesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-159">Gets the IBgpServiceCommunitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckDnsNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;&gt; CheckDnsNameAvailabilityWithHttpMessagesAsync (string location, string domainNameLabel = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;&gt; CheckDnsNameAvailabilityWithHttpMessagesAsync(string location, string domainNameLabel, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.CheckDnsNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckDnsNameAvailabilityWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;&gt;&#xA;override this.CheckDnsNameAvailabilityWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;&gt;" Usage="networkManagementClient.CheckDnsNameAvailabilityWithHttpMessagesAsync (location, domainNameLabel, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.CheckDnsNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient/&lt;CheckDnsNameAvailabilityWithHttpMessagesAsync&gt;d__178))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="8b225-160">ドメイン名の場所です。</span><span class="sxs-lookup"><span data-stu-id="8b225-160">The location of the domain name.</span></span>
            </param>
        <param name="domainNameLabel">
            <span data-ttu-id="8b225-161">検証するドメイン名。</span><span class="sxs-lookup"><span data-stu-id="8b225-161">The domain name to be verified.</span></span> <span data-ttu-id="8b225-162">次の正規表現に従ってください: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$ です。</span><span class="sxs-lookup"><span data-stu-id="8b225-162">It must conform to the following regular expression: ^[a-z][a-z0-9-]{1,61}[a-z0-9]$.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8b225-163">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8b225-163">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b225-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b225-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b225-165">Cloudapp.net ゾーンで、ドメイン名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="8b225-165">Checks whether a domain name in the cloudapp.net zone is available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8b225-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8b225-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8b225-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-168">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8b225-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8b225-169">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="8b225-170">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8b225-170">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-171">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="8b225-171">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecurityRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IDefaultSecurityRulesOperations DefaultSecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IDefaultSecurityRulesOperations DefaultSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.DefaultSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecurityRules As IDefaultSecurityRulesOperations" />
      <MemberSignature Language="F#" Value="member this.DefaultSecurityRules : Microsoft.Azure.Management.Network.Fluent.IDefaultSecurityRulesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.DefaultSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IDefaultSecurityRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-172">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b225-172">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuitAuthorizations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations ExpressRouteCircuitAuthorizations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations ExpressRouteCircuitAuthorizations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuitAuthorizations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuitAuthorizations As IExpressRouteCircuitAuthorizationsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuitAuthorizations : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuitAuthorizations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-173">IExpressRouteCircuitAuthorizationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-173">Gets the IExpressRouteCircuitAuthorizationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuitPeerings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations ExpressRouteCircuitPeerings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations ExpressRouteCircuitPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuitPeerings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuitPeerings As IExpressRouteCircuitPeeringsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuitPeerings : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuitPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-174">IExpressRouteCircuitPeeringsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-174">Gets the IExpressRouteCircuitPeeringsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations ExpressRouteCircuits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations ExpressRouteCircuits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuits" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuits As IExpressRouteCircuitsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuits : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteCircuits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-175">IExpressRouteCircuitsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-175">Gets the IExpressRouteCircuitsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteServiceProviders">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations ExpressRouteServiceProviders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations ExpressRouteServiceProviders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteServiceProviders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteServiceProviders As IExpressRouteServiceProvidersOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteServiceProviders : Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.ExpressRouteServiceProviders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-176">IExpressRouteServiceProvidersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-176">Gets the IExpressRouteServiceProvidersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-177">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="8b225-177">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="8b225-178">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="8b225-178">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IInboundNatRulesOperations InboundNatRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IInboundNatRulesOperations InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InboundNatRules As IInboundNatRulesOperations" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : Microsoft.Azure.Management.Network.Fluent.IInboundNatRulesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IInboundNatRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackendAddressPoolsOperations LoadBalancerBackendAddressPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackendAddressPoolsOperations LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerBackendAddressPools As ILoadBalancerBackendAddressPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackendAddressPoolsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackendAddressPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerFrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontendIPConfigurationsOperations LoadBalancerFrontendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontendIPConfigurationsOperations LoadBalancerFrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerFrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerFrontendIPConfigurations As ILoadBalancerFrontendIPConfigurationsOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerFrontendIPConfigurations : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontendIPConfigurationsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerFrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontendIPConfigurationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerLoadBalancingRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerLoadBalancingRulesOperations LoadBalancerLoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerLoadBalancingRulesOperations LoadBalancerLoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerLoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerLoadBalancingRules As ILoadBalancerLoadBalancingRulesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerLoadBalancingRules : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerLoadBalancingRulesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerLoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerLoadBalancingRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerNetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerNetworkInterfacesOperations LoadBalancerNetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerNetworkInterfacesOperations LoadBalancerNetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerNetworkInterfaces As ILoadBalancerNetworkInterfacesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerNetworkInterfaces : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerNetworkInterfacesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerNetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerNetworkInterfacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbesOperations LoadBalancerProbes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbesOperations LoadBalancerProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerProbes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerProbes As ILoadBalancerProbesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerProbes : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancerProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations LoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations LoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancers As ILoadBalancersOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancers : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LoadBalancers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-179">ILoadBalancersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-179">Gets the ILoadBalancersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations LocalNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations LocalNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LocalNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalNetworkGateways As ILocalNetworkGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateways : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LocalNetworkGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-180">ILocalNetworkGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-180">Gets the ILocalNetworkGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-181">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="8b225-181">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="8b225-182">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="8b225-182">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIPConfigurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceIPConfigurationsOperations NetworkInterfaceIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceIPConfigurationsOperations NetworkInterfaceIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaceIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIPConfigurations As INetworkInterfaceIPConfigurationsOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIPConfigurations : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceIPConfigurationsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaceIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceIPConfigurationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceLoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations NetworkInterfaceLoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations NetworkInterfaceLoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaceLoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceLoadBalancers As INetworkInterfaceLoadBalancersOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceLoadBalancers : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaceLoadBalancers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As INetworkInterfacesOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-183">INetworkInterfacesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-183">Gets the INetworkInterfacesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations NetworkSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations NetworkSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroups As INetworkSecurityGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroups : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-184">INetworkSecurityGroupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-184">Gets the INetworkSecurityGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWatchers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations NetworkWatchers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations NetworkWatchers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkWatchers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWatchers As INetworkWatchersOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkWatchers : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.NetworkWatchers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-185">INetworkWatchersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-185">Gets the INetworkWatchersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptures">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations PacketCaptures { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations PacketCaptures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.PacketCaptures" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PacketCaptures As IPacketCapturesOperations" />
      <MemberSignature Language="F#" Value="member this.PacketCaptures : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.PacketCaptures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-186">IPacketCapturesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-186">Gets the IPacketCapturesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddresses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations PublicIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations PublicIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.PublicIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddresses As IPublicIPAddressesOperations" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddresses : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.PublicIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-187">IPublicIPAddressesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-187">Gets the IPublicIPAddressesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilterRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations RouteFilterRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations RouteFilterRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteFilterRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteFilterRules As IRouteFilterRulesOperations" />
      <MemberSignature Language="F#" Value="member this.RouteFilterRules : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteFilterRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-188">IRouteFilterRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-188">Gets the IRouteFilterRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations RouteFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations RouteFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteFilters As IRouteFiltersOperations" />
      <MemberSignature Language="F#" Value="member this.RouteFilters : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-189">IRouteFiltersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-189">Gets the IRouteFiltersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRoutesOperations Routes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Routes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Routes As IRoutesOperations" />
      <MemberSignature Language="F#" Value="member this.Routes : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRoutesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-190">IRoutesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-190">Gets the IRoutesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTables">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations RouteTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations RouteTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteTables As IRouteTablesOperations" />
      <MemberSignature Language="F#" Value="member this.RouteTables : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.RouteTables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-191">IRouteTablesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-191">Gets the IRouteTablesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations SecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityRules As ISecurityRulesOperations" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-192">ISecurityRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-192">Gets the ISecurityRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-193">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b225-193">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As ISubnetsOperations" />
      <MemberSignature Language="F#" Value="member this.Subnets : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-194">ISubnetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-194">Gets the ISubnetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-195">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報。</span><span class="sxs-lookup"><span data-stu-id="8b225-195">The subscription credentials which uniquely identify the Microsoft Azure subscription.</span></span> <span data-ttu-id="8b225-196">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="8b225-196">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IUsagesOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IUsagesOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usages As IUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.Network.Fluent.IUsagesOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.Usages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-197">IUsagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-197">Gets the IUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGatewayConnections">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations VirtualNetworkGatewayConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations VirtualNetworkGatewayConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkGatewayConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGatewayConnections As IVirtualNetworkGatewayConnectionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGatewayConnections : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkGatewayConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-198">IVirtualNetworkGatewayConnectionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-198">Gets the IVirtualNetworkGatewayConnectionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations VirtualNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations VirtualNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGateways As IVirtualNetworkGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateways : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-199">IVirtualNetworkGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-199">Gets the IVirtualNetworkGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations VirtualNetworkPeerings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkPeerings As IVirtualNetworkPeeringsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-200">IVirtualNetworkPeeringsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-200">Gets the IVirtualNetworkPeeringsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworksOperations VirtualNetworks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworksOperations VirtualNetworks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworks As IVirtualNetworksOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworks : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworksOperations" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClient.VirtualNetworks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b225-201">IVirtualNetworksOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b225-201">Gets the IVirtualNetworksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>