<Type Name="DataFactoryManagementClient" FullName="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient">
  <TypeSignature Language="C#" Value="public class DataFactoryManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataFactoryManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient&gt; implements class Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataFactoryManagementClient&#xA;Inherits ServiceClient(Of DataFactoryManagementClient)&#xA;Implements IAzureClient, IDataFactoryManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataFactoryManagementClient = class&#xA;    inherit ServiceClient&lt;DataFactoryManagementClient&gt;&#xA;    interface IDataFactoryManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient</InterfaceName>
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
            <span data-ttu-id="55ae8-101">Azure データ ファクトリ V2 管理 API は、Azure データ ファクトリ V2 サービスと web サービスを操作の RESTful セットを提供します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-101">The Azure Data Factory V2 management API provides a RESTful set of web services that interact with Azure Data Factory V2 services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataFactoryManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-102">Optional.</span></span> <span data-ttu-id="55ae8-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-104">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-104">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-105">必須。</span><span class="sxs-lookup"><span data-stu-id="55ae8-105">Required.</span></span> <span data-ttu-id="55ae8-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-107">Optional.</span></span> <span data-ttu-id="55ae8-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-109">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-109">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataFactoryManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-111">Optional.</span></span> <span data-ttu-id="55ae8-112">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-113">Optional.</span></span> <span data-ttu-id="55ae8-114">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-115">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-115">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataFactoryManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-116">Optional.</span></span> <span data-ttu-id="55ae8-117">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="55ae8-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-118">Optional.</span></span> <span data-ttu-id="55ae8-119">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-120">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-120">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-122">必須。</span><span class="sxs-lookup"><span data-stu-id="55ae8-122">Required.</span></span> <span data-ttu-id="55ae8-123">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="55ae8-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-124">Optional.</span></span> <span data-ttu-id="55ae8-125">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-126">Optional.</span></span> <span data-ttu-id="55ae8-127">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-128">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-128">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-130">Optional.</span></span> <span data-ttu-id="55ae8-131">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="55ae8-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="55ae8-132">必須。</span><span class="sxs-lookup"><span data-stu-id="55ae8-132">Required.</span></span> <span data-ttu-id="55ae8-133">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-134">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-134">Optional.</span></span> <span data-ttu-id="55ae8-135">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-136">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-136">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataFactoryManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-138">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-138">Optional.</span></span> <span data-ttu-id="55ae8-139">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="55ae8-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="55ae8-140">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-140">Optional.</span></span> <span data-ttu-id="55ae8-141">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-142">Optional.</span></span> <span data-ttu-id="55ae8-143">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-144">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-144">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="55ae8-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-146">Optional.</span></span> <span data-ttu-id="55ae8-147">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="55ae8-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="55ae8-148">必須。</span><span class="sxs-lookup"><span data-stu-id="55ae8-148">Required.</span></span> <span data-ttu-id="55ae8-149">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="55ae8-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-150">Optional.</span></span> <span data-ttu-id="55ae8-151">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="55ae8-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="55ae8-152">Optional.</span></span> <span data-ttu-id="55ae8-153">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="55ae8-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55ae8-154">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-154">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55ae8-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-156">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IActivityRunsOperations ActivityRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations ActivityRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.ActivityRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityRuns As IActivityRunsOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityRuns : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.ActivityRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IActivityRunsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-157">IActivityRunsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-157">Gets the IActivityRunsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-158">API のバージョン。</span><span class="sxs-lookup"><span data-stu-id="55ae8-158">The API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-159">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="55ae8-159">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-160">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-160">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IDatasetsOperations Datasets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IDatasetsOperations Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Datasets As IDatasetsOperations" />
      <MemberSignature Language="F#" Value="member this.Datasets : Microsoft.Azure.Management.DataFactory.IDatasetsOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IDatasetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-161">IDatasetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-161">Gets the IDatasetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-162">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-162">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Factories">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IFactoriesOperations Factories { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IFactoriesOperations Factories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Factories" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Factories As IFactoriesOperations" />
      <MemberSignature Language="F#" Value="member this.Factories : Microsoft.Azure.Management.DataFactory.IFactoriesOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Factories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IFactoriesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-163">IFactoriesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-163">Gets the IFactoriesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-164">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="55ae8-164">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="55ae8-165">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-165">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrationRuntimeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations IntegrationRuntimeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations IntegrationRuntimeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.IntegrationRuntimeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IntegrationRuntimeNodes As IIntegrationRuntimeNodesOperations" />
      <MemberSignature Language="F#" Value="member this.IntegrationRuntimeNodes : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.IntegrationRuntimeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-166">IIntegrationRuntimeNodesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-166">Gets the IIntegrationRuntimeNodesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrationRuntimes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations IntegrationRuntimes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations IntegrationRuntimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.IntegrationRuntimes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IntegrationRuntimes As IIntegrationRuntimesOperations" />
      <MemberSignature Language="F#" Value="member this.IntegrationRuntimes : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.IntegrationRuntimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-167">IIntegrationRuntimesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-167">Gets the IIntegrationRuntimesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServices As ILinkedServicesOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-168">ILinkedServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-168">Gets the ILinkedServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-169">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-169">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="55ae8-170">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-170">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.DataFactory.IOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-171">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-171">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations PipelineRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations PipelineRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.PipelineRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineRuns As IPipelineRunsOperations" />
      <MemberSignature Language="F#" Value="member this.PipelineRuns : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.PipelineRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-172">IPipelineRunsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-172">Gets the IPipelineRunsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IPipelinesOperations Pipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IPipelinesOperations Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pipelines As IPipelinesOperations" />
      <MemberSignature Language="F#" Value="member this.Pipelines : Microsoft.Azure.Management.DataFactory.IPipelinesOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Pipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IPipelinesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-173">IPipelinesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-173">Gets the IPipelinesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-174">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-174">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-175">サブスクリプションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="55ae8-175">The subscription identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Triggers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.ITriggersOperations Triggers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.ITriggersOperations Triggers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Triggers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Triggers As ITriggersOperations" />
      <MemberSignature Language="F#" Value="member this.Triggers : Microsoft.Azure.Management.DataFactory.ITriggersOperations" Usage="Microsoft.Azure.Management.DataFactory.DataFactoryManagementClient.Triggers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.ITriggersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ae8-176">ITriggersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ae8-176">Gets the ITriggersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>