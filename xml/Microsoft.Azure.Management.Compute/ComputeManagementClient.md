<Type Name="ComputeManagementClient" FullName="Microsoft.Azure.Management.Compute.ComputeManagementClient">
  <TypeSignature Language="C#" Value="public class ComputeManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Compute.ComputeManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Compute.IComputeManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.Compute.ComputeManagementClient&gt; implements class Microsoft.Azure.Management.Compute.IComputeManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ComputeManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeManagementClient&#xA;Inherits ServiceClient(Of ComputeManagementClient)&#xA;Implements IAzureClient, IComputeManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type ComputeManagementClient = class&#xA;    inherit ServiceClient&lt;ComputeManagementClient&gt;&#xA;    interface IComputeManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Compute.ComputeManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Compute.ComputeManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.IComputeManagementClient</InterfaceName>
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
            <span data-ttu-id="f5d01-101">クライアントを計算します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-101">Compute Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ComputeManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-102">Optional.</span></span> <span data-ttu-id="f5d01-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-104">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-104">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-105">必須。</span><span class="sxs-lookup"><span data-stu-id="f5d01-105">Required.</span></span> <span data-ttu-id="f5d01-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-107">Optional.</span></span> <span data-ttu-id="f5d01-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-109">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-109">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ComputeManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-111">Optional.</span></span> <span data-ttu-id="f5d01-112">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-113">Optional.</span></span> <span data-ttu-id="f5d01-114">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-115">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-115">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ComputeManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-116">Optional.</span></span> <span data-ttu-id="f5d01-117">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f5d01-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-118">Optional.</span></span> <span data-ttu-id="f5d01-119">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-120">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-120">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-122">必須。</span><span class="sxs-lookup"><span data-stu-id="f5d01-122">Required.</span></span> <span data-ttu-id="f5d01-123">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f5d01-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-124">Optional.</span></span> <span data-ttu-id="f5d01-125">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-126">Optional.</span></span> <span data-ttu-id="f5d01-127">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-128">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-128">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-130">Optional.</span></span> <span data-ttu-id="f5d01-131">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f5d01-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f5d01-132">必須。</span><span class="sxs-lookup"><span data-stu-id="f5d01-132">Required.</span></span> <span data-ttu-id="f5d01-133">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-134">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-134">Optional.</span></span> <span data-ttu-id="f5d01-135">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-136">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-136">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ComputeManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-138">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-138">Optional.</span></span> <span data-ttu-id="f5d01-139">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f5d01-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f5d01-140">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-140">Optional.</span></span> <span data-ttu-id="f5d01-141">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-142">Optional.</span></span> <span data-ttu-id="f5d01-143">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-144">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-144">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ComputeManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.ComputeManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Compute.ComputeManagementClient" Usage="new Microsoft.Azure.Management.Compute.ComputeManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f5d01-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-146">Optional.</span></span> <span data-ttu-id="f5d01-147">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f5d01-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f5d01-148">必須。</span><span class="sxs-lookup"><span data-stu-id="f5d01-148">Required.</span></span> <span data-ttu-id="f5d01-149">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f5d01-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-150">Optional.</span></span> <span data-ttu-id="f5d01-151">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f5d01-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f5d01-152">Optional.</span></span> <span data-ttu-id="f5d01-153">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="f5d01-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d01-154">ComputeManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-154">Initializes a new instance of the ComputeManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f5d01-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Compute.IComputeManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-156">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations AvailabilitySets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations AvailabilitySets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.AvailabilitySets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySets As IAvailabilitySetsOperations" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySets : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.AvailabilitySets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-157">IAvailabilitySetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-157">Gets the IAvailabilitySetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Compute.IComputeManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-158">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="f5d01-158">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IContainerServicesOperations ContainerServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IContainerServicesOperations ContainerServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.ContainerServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerServices As IContainerServicesOperations" />
      <MemberSignature Language="F#" Value="member this.ContainerServices : Microsoft.Azure.Management.Compute.IContainerServicesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.ContainerServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IContainerServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-159">IContainerServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-159">Gets the IContainerServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-160">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-160">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-161">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-161">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IDisksOperations Disks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IDisksOperations Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.Disks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Disks As IDisksOperations" />
      <MemberSignature Language="F#" Value="member this.Disks : Microsoft.Azure.Management.Compute.IDisksOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IDisksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-162">IDisksOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-162">Gets the IDisksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Compute.IComputeManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-163">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="f5d01-163">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="f5d01-164">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-164">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IImagesOperations Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IImagesOperations Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As IImagesOperations" />
      <MemberSignature Language="F#" Value="member this.Images : Microsoft.Azure.Management.Compute.IImagesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-165">IImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-165">Gets the IImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Compute.IComputeManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-166">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-166">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="f5d01-167">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="f5d01-167">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IResourceSkusOperations ResourceSkus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IResourceSkusOperations ResourceSkus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.ResourceSkus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceSkus As IResourceSkusOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceSkus : Microsoft.Azure.Management.Compute.IResourceSkusOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.ResourceSkus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IResourceSkusOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-168">IResourceSkusOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-168">Gets the IResourceSkusOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-169">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-169">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshots">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.ISnapshotsOperations Snapshots { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.ISnapshotsOperations Snapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.Snapshots" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Snapshots As ISnapshotsOperations" />
      <MemberSignature Language="F#" Value="member this.Snapshots : Microsoft.Azure.Management.Compute.ISnapshotsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.Snapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.ISnapshotsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-170">ISnapshotsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-170">Gets the ISnapshotsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Compute.IComputeManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-171">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報。</span><span class="sxs-lookup"><span data-stu-id="f5d01-171">Subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="f5d01-172">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-172">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IUsageOperations Usage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IUsageOperations Usage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.Usage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usage As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usage : Microsoft.Azure.Management.Compute.IUsageOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.Usage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-173">IUsageOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-173">Gets the IUsageOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensionImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensionImages As IVirtualMachineExtensionImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensionImages : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-174">IVirtualMachineExtensionImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-174">Gets the IVirtualMachineExtensionImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations VirtualMachineExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations VirtualMachineExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensions As IVirtualMachineExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensions : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-175">IVirtualMachineExtensionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-175">Gets the IVirtualMachineExtensionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations VirtualMachineImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations VirtualMachineImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImages As IVirtualMachineImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImages : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-176">IVirtualMachineImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-176">Gets the IVirtualMachineImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineRunCommands">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineRunCommands" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineRunCommands As IVirtualMachineRunCommandsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineRunCommands : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineRunCommands" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-177">IVirtualMachineRunCommandsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-177">Gets the IVirtualMachineRunCommandsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachinesOperations VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachinesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachinesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-178">IVirtualMachinesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-178">Gets the IVirtualMachinesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetExtensions As IVirtualMachineScaleSetExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetExtensions : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-179">IVirtualMachineScaleSetExtensionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-179">Gets the IVirtualMachineScaleSetExtensionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetRollingUpgrades">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations VirtualMachineScaleSetRollingUpgrades { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations VirtualMachineScaleSetRollingUpgrades" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetRollingUpgrades" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetRollingUpgrades As IVirtualMachineScaleSetRollingUpgradesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetRollingUpgrades : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetRollingUpgrades" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-180">IVirtualMachineScaleSetRollingUpgradesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-180">Gets the IVirtualMachineScaleSetRollingUpgradesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSets As IVirtualMachineScaleSetsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSets : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-181">IVirtualMachineScaleSetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-181">Gets the IVirtualMachineScaleSetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetVMs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetVMs As IVirtualMachineScaleSetVMsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetVMs : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-182">IVirtualMachineScaleSetVMsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-182">Gets the IVirtualMachineScaleSetVMsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSizes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations VirtualMachineSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations VirtualMachineSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSizes As IVirtualMachineSizesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSizes : Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations" Usage="Microsoft.Azure.Management.Compute.ComputeManagementClient.VirtualMachineSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d01-183">IVirtualMachineSizesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d01-183">Gets the IVirtualMachineSizesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>