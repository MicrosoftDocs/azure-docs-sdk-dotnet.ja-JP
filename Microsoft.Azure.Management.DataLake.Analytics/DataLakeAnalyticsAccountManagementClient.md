<Type Name="DataLakeAnalyticsAccountManagementClient" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccountManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt; implements class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccountManagementClient&#xA;Inherits ServiceClient(Of DataLakeAnalyticsAccountManagementClient)&#xA;Implements IAzureClient, IDataLakeAnalyticsAccountManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccountManagementClient = class&#xA;    inherit ServiceClient&lt;DataLakeAnalyticsAccountManagementClient&gt;&#xA;    interface IDataLakeAnalyticsAccountManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient</InterfaceName>
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
            <span data-ttu-id="634cc-101">Data Lake Store アカウント管理クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="634cc-101">Creates a Data Lake Store account management client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="634cc-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-102">Optional.</span></span> <span data-ttu-id="634cc-103">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-104">DataLakeAnalyticsAccountManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-104">Initializes a new instance of the DataLakeAnalyticsAccountManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="634cc-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-105">Optional.</span></span> <span data-ttu-id="634cc-106">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-106">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-107">Optional.</span></span> <span data-ttu-id="634cc-108">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-109">DataLakeAnalyticsAccountManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-109">Initializes a new instance of the DataLakeAnalyticsAccountManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="634cc-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-110">Optional.</span></span> <span data-ttu-id="634cc-111">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="634cc-111">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-112">Optional.</span></span> <span data-ttu-id="634cc-113">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-113">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-114">DataLakeAnalyticsAccountManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-114">Initializes a new instance of the DataLakeAnalyticsAccountManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="634cc-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="634cc-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClientCredentials * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (credentials, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
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
            <span data-ttu-id="634cc-116">必須。</span><span class="sxs-lookup"><span data-stu-id="634cc-116">Required.</span></span> <span data-ttu-id="634cc-117">Azure サブスクリプションの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-117">Gets Azure subscription credentials.</span></span>
            </param>
        <param name="userAgentAssemblyVersion">
            <span data-ttu-id="634cc-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-118">Optional.</span></span> <span data-ttu-id="634cc-119">すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。</span><span class="sxs-lookup"><span data-stu-id="634cc-119">The version string that should be sent in the user-agent header for all requests.</span></span> <span data-ttu-id="634cc-120">既定では、SDK の現在のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="634cc-120">The default is the current version of the SDK.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-121">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-121">Optional.</span></span> <span data-ttu-id="634cc-122">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-122">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-123">DataLakeStoreManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-123">Initializes a new instance of the DataLakeStoreManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="634cc-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-124">Optional.</span></span> <span data-ttu-id="634cc-125">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="634cc-125">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="634cc-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-126">Optional.</span></span> <span data-ttu-id="634cc-127">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-127">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-128">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-128">Optional.</span></span> <span data-ttu-id="634cc-129">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-129">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-130">DataLakeAnalyticsAccountManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-130">Initializes a new instance of the DataLakeAnalyticsAccountManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="634cc-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="634cc-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (credentials, rootHandler, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
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
            <span data-ttu-id="634cc-132">必須。</span><span class="sxs-lookup"><span data-stu-id="634cc-132">Required.</span></span> <span data-ttu-id="634cc-133">Azure サブスクリプションの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-133">Gets Azure subscription credentials.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="634cc-134">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-134">Optional.</span></span> <span data-ttu-id="634cc-135">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-135">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="userAgentAssemblyVersion">
            <span data-ttu-id="634cc-136">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-136">Optional.</span></span> <span data-ttu-id="634cc-137">すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。</span><span class="sxs-lookup"><span data-stu-id="634cc-137">The version string that should be sent in the user-agent header for all requests.</span></span> <span data-ttu-id="634cc-138">既定では、SDK の現在のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="634cc-138">The default is the current version of the SDK.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-139">Optional.</span></span> <span data-ttu-id="634cc-140">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-140">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-141">DataLakeStoreManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-141">Initializes a new instance of the DataLakeStoreManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, credentials, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
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
            <span data-ttu-id="634cc-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-142">Optional.</span></span> <span data-ttu-id="634cc-143">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="634cc-143">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="634cc-144">必須。</span><span class="sxs-lookup"><span data-stu-id="634cc-144">Required.</span></span> <span data-ttu-id="634cc-145">Azure サブスクリプションの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-145">Gets Azure subscription credentials.</span></span>
            </param>
        <param name="userAgentAssemblyVersion">
            <span data-ttu-id="634cc-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-146">Optional.</span></span> <span data-ttu-id="634cc-147">すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。</span><span class="sxs-lookup"><span data-stu-id="634cc-147">The version string that should be sent in the user-agent header for all requests.</span></span> <span data-ttu-id="634cc-148">既定では、SDK の現在のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="634cc-148">The default is the current version of the SDK.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-149">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-149">Optional.</span></span> <span data-ttu-id="634cc-150">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-150">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-151">DataLakeStoreManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-151">Initializes a new instance of the DataLakeStoreManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, credentials, rootHandler, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
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
            <span data-ttu-id="634cc-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-152">Optional.</span></span> <span data-ttu-id="634cc-153">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="634cc-153">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="634cc-154">必須。</span><span class="sxs-lookup"><span data-stu-id="634cc-154">Required.</span></span> <span data-ttu-id="634cc-155">Azure サブスクリプションの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-155">Gets Azure subscription credentials.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="634cc-156">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-156">Optional.</span></span> <span data-ttu-id="634cc-157">Http トランスポートを処理するために使用する http クライアント ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-157">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="userAgentAssemblyVersion">
            <span data-ttu-id="634cc-158">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-158">Optional.</span></span> <span data-ttu-id="634cc-159">すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。</span><span class="sxs-lookup"><span data-stu-id="634cc-159">The version string that should be sent in the user-agent header for all requests.</span></span> <span data-ttu-id="634cc-160">既定では、SDK の現在のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="634cc-160">The default is the current version of the SDK.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="634cc-161">省略可能。</span><span class="sxs-lookup"><span data-stu-id="634cc-161">Optional.</span></span> <span data-ttu-id="634cc-162">Http クライアント パイプラインに追加するデリゲート ハンドラー。</span><span class="sxs-lookup"><span data-stu-id="634cc-162">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="634cc-163">DataLakeStoreManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="634cc-163">Initializes a new instance of the DataLakeStoreManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-164">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="634cc-164">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Account">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations Account { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations Account" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Account" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Account As IAccountOperations" />
      <MemberSignature Language="F#" Value="member this.Account : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Account" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-165">IAccountOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-165">Gets the IAccountOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-166">クライアント Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="634cc-166">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-167">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="634cc-167">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputePolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations ComputePolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations ComputePolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ComputePolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputePolicies As IComputePoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ComputePolicies : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ComputePolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-168">IComputePoliciesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-168">Gets the IComputePoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-169">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="634cc-169">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations DataLakeStoreAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations DataLakeStoreAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DataLakeStoreAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataLakeStoreAccounts As IDataLakeStoreAccountsOperations" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreAccounts : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DataLakeStoreAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-170">IDataLakeStoreAccountsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-170">Gets the IDataLakeStoreAccountsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-171">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="634cc-171">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations FirewallRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirewallRules As IFirewallRulesOperations" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-172">IFirewallRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-172">Gets the IFirewallRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-173">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="634cc-173">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="634cc-174">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="634cc-174">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-175">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="634cc-175">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="634cc-176">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="634cc-176">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-177">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="634cc-177">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations StorageAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccounts As IStorageAccountsOperations" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-178">IStorageAccountsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-178">Gets the IStorageAccountsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="634cc-179">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="634cc-179">Get subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="634cc-180">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="634cc-180">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>