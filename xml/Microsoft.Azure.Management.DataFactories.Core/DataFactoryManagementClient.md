<Type Name="DataFactoryManagementClient" FullName="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient">
  <TypeSignature Language="C#" Value="public class DataFactoryManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataFactoryManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; implements class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataFactoryManagementClient&#xA;Inherits ServiceClient(Of DataFactoryManagementClient)&#xA;Implements IDataFactoryManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataFactoryManagementClient = class&#xA;    inherit ServiceClient&lt;DataFactoryManagementClient&gt;&#xA;    interface IDataFactoryManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient</InterfaceName>
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
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-101">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-101">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="fdb27-102">必須。</span><span class="sxs-lookup"><span data-stu-id="fdb27-102">Required.</span></span> <span data-ttu-id="fdb27-103">サブスクリプション ID によって一意に識別、Windows Azure サブスクリプションを作成するときに</span><span class="sxs-lookup"><span data-stu-id="fdb27-103">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="fdb27-104">サブスクリプション ID では、サービス管理 API に対して行うすべての呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-104">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="fdb27-105">Windows Azure サービス ManagementAPI では、SSL 経由で管理証明書の相互認証を使用して、サービスに対する要求が安全であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-105">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="fdb27-106">匿名要求は許可されていません。</span><span class="sxs-lookup"><span data-stu-id="fdb27-106">No anonymous requests are allowed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-107">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-107">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="fdb27-108">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="fdb27-108">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-109">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-109">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="fdb27-110">必須。</span><span class="sxs-lookup"><span data-stu-id="fdb27-110">Required.</span></span> <span data-ttu-id="fdb27-111">サブスクリプション ID によって一意に識別、Windows Azure サブスクリプションを作成するときに</span><span class="sxs-lookup"><span data-stu-id="fdb27-111">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="fdb27-112">サブスクリプション ID では、サービス管理 API に対して行うすべての呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-112">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="fdb27-113">Windows Azure サービス ManagementAPI では、SSL 経由で管理証明書の相互認証を使用して、サービスに対する要求が安全であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-113">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="fdb27-114">匿名要求は許可されていません。</span><span class="sxs-lookup"><span data-stu-id="fdb27-114">No anonymous requests are allowed.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="fdb27-115">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="fdb27-115">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-116">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-116">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="fdb27-117">必須。</span><span class="sxs-lookup"><span data-stu-id="fdb27-117">Required.</span></span> <span data-ttu-id="fdb27-118">サブスクリプション ID によって一意に識別、Windows Azure サブスクリプションを作成するときに</span><span class="sxs-lookup"><span data-stu-id="fdb27-118">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="fdb27-119">サブスクリプション ID では、サービス管理 API に対して行うすべての呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-119">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="fdb27-120">Windows Azure サービス ManagementAPI では、SSL 経由で管理証明書の相互認証を使用して、サービスに対する要求が安全であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-120">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="fdb27-121">匿名要求は許可されていません。</span><span class="sxs-lookup"><span data-stu-id="fdb27-121">No anonymous requests are allowed.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="fdb27-122">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fdb27-122">Optional.</span></span> <span data-ttu-id="fdb27-123">すべてのサービス管理要求のベースとして使用する URI。</span><span class="sxs-lookup"><span data-stu-id="fdb27-123">The URI used as the base for all Service Management requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-124">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-124">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="fdb27-125">必須。</span><span class="sxs-lookup"><span data-stu-id="fdb27-125">Required.</span></span> <span data-ttu-id="fdb27-126">サブスクリプション ID によって一意に識別、Windows Azure サブスクリプションを作成するときに</span><span class="sxs-lookup"><span data-stu-id="fdb27-126">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="fdb27-127">サブスクリプション ID では、サービス管理 API に対して行うすべての呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-127">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="fdb27-128">Windows Azure サービス ManagementAPI では、SSL 経由で管理証明書の相互認証を使用して、サービスに対する要求が安全であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-128">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="fdb27-129">匿名要求は許可されていません。</span><span class="sxs-lookup"><span data-stu-id="fdb27-129">No anonymous requests are allowed.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="fdb27-130">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fdb27-130">Optional.</span></span> <span data-ttu-id="fdb27-131">すべてのサービス管理要求のベースとして使用する URI。</span><span class="sxs-lookup"><span data-stu-id="fdb27-131">The URI used as the base for all Service Management requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="fdb27-132">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="fdb27-132">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-133">DataFactoryManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-133">Initializes a new instance of the DataFactoryManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations ActivityTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations ActivityTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ActivityTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ActivityTypes As IActivityTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityTypes : Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ActivityTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-134">データ ファクトリ Activitytype を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-134">Operations for managing data factory ActivityTypes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityWindows">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations ActivityWindows { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations ActivityWindows" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ActivityWindows" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ActivityWindows As IActivityWindowOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityWindows : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ActivityWindows" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityWindows</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-135">アクティビティ ウィンドウの操作。</span><span class="sxs-lookup"><span data-stu-id="fdb27-135">Operations for activity windows.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-136">すべてのサービス管理要求のベースとして使用する URI。</span><span class="sxs-lookup"><span data-stu-id="fdb27-136">The URI used as the base for all Service Management requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of DataFactoryManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; -&gt; unit" Usage="dataFactoryManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="fdb27-137">複製する DataFactoryManagementClient のインスタンス</span><span class="sxs-lookup"><span data-stu-id="fdb27-137">Instance of DataFactoryManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-138">現在のインスタンスから別の DataFactoryManagementClient インスタンスにプロパティのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-138">Clones properties from current instance to another DataFactoryManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations ComputeTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations ComputeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ComputeTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ComputeTypes As IComputeTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ComputeTypes : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.ComputeTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ComputeTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-139">データ ファクトリ Computetype を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-139">Operations for managing data factory ComputeTypes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-140">サブスクリプション ID によって一意に識別、Windows Azure サブスクリプションを作成するときに</span><span class="sxs-lookup"><span data-stu-id="fdb27-140">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="fdb27-141">サブスクリプション ID では、サービス管理 API に対して行うすべての呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-141">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="fdb27-142">Windows Azure サービス ManagementAPI では、SSL 経由で管理証明書の相互認証を使用して、サービスに対する要求が安全であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-142">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="fdb27-143">匿名要求は許可されていません。</span><span class="sxs-lookup"><span data-stu-id="fdb27-143">No anonymous requests are allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataFactories">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations DataFactories { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations DataFactories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataFactories" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DataFactories As IDataFactoryOperations" />
      <MemberSignature Language="F#" Value="member this.DataFactories : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataFactories" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataFactories</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-144">データ ファクトリを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-144">Operations for managing data factories.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations Datasets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Datasets As IDatasetOperations" />
      <MemberSignature Language="F#" Value="member this.Datasets : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Datasets" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Datasets</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-145">データセットを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-145">Operations for managing datasets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSliceRuns">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations DataSliceRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations DataSliceRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataSliceRuns" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DataSliceRuns As IDataSliceRunOperations" />
      <MemberSignature Language="F#" Value="member this.DataSliceRuns : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataSliceRuns" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSliceRuns</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-146">データ スライスの実行を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-146">Operations for managing data slice runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSlices">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations DataSlices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations DataSlices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataSlices" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DataSlices As IDataSliceOperations" />
      <MemberSignature Language="F#" Value="member this.DataSlices : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.DataSlices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSlices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-147">データ スライスを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-147">Operations for managing data slices.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateways">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations Gateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations Gateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Gateways" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Gateways As IGatewayOperations" />
      <MemberSignature Language="F#" Value="member this.Gateways : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Gateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Gateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-148">データ ファクトリのゲートウェイを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-148">Operations for managing data factory gateways.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongRunningOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.GetLongRunningOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLongRunningOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.GetLongRunningOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="dataFactoryManagementClient.GetLongRunningOperationStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.GetLongRunningOperationStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient/&lt;GetLongRunningOperationStatusAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="fdb27-149">必須。</span><span class="sxs-lookup"><span data-stu-id="fdb27-149">Required.</span></span> <span data-ttu-id="fdb27-150">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-150">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdb27-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fdb27-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdb27-152">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-152">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="fdb27-153">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-153">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fdb27-154">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-154">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestUri">
      <MemberSignature Language="C#" Value="public string GetRequestUri (Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetRequestUri(class System.Action`1&lt;class Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.GetRequestUri(System.Action{Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRequestUri (operation As Action(Of DataFactoryManagementClient)) As String" />
      <MemberSignature Language="F#" Value="member this.GetRequestUri : Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; -&gt; string" Usage="dataFactoryManagementClient.GetRequestUri operation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="System.Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="operation"></param>
        <summary>
            <span data-ttu-id="fdb27-155">(実際に呼び出しません RP。)、指定した RP 操作を実行するヒュドラ クライアントを使用する url を返します</span><span class="sxs-lookup"><span data-stu-id="fdb27-155">Returns the url that the Hydra client would use to execute the given RP operation (doesn't actually call the RP.)</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResponseBody">
      <MemberSignature Language="C#" Value="public string GetResponseBody (Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetResponseBody(class System.Action`1&lt;class Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.GetResponseBody(System.Action{Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResponseBody (operation As Action(Of DataFactoryManagementClient)) As String" />
      <MemberSignature Language="F#" Value="member this.GetResponseBody : Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt; -&gt; string" Usage="dataFactoryManagementClient.GetResponseBody operation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="System.Action&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="operation"></param>
        <summary>
            <span data-ttu-id="fdb27-156">RP に特定の呼び出しを実行し、応答コンテンツ (つまり raw json) を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-156">Executes the given call to the RP and returns the response content (i.e. raw json).</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResponseBodyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetResponseBodyAsync (Func&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient,System.Threading.Tasks.Task&gt; operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetResponseBodyAsync(class System.Func`2&lt;class Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient, class System.Threading.Tasks.Task&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.GetResponseBodyAsync(System.Func{Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResponseBodyAsync (operation As Func(Of DataFactoryManagementClient, Task)) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetResponseBodyAsync : Func&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient, System.Threading.Tasks.Task&gt; -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="dataFactoryManagementClient.GetResponseBodyAsync operation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient/&lt;GetResponseBodyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="System.Func&lt;Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="operation"></param>
        <summary>
            <span data-ttu-id="fdb27-157">RP に特定の呼び出しを実行し、応答コンテンツ (つまり raw json) を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-157">Executes the given call to the RP and returns the response content (i.e. raw json).</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hubs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IHubOperations Hubs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IHubOperations Hubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Hubs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Hubs As IHubOperations" />
      <MemberSignature Language="F#" Value="member this.Hubs : Microsoft.Azure.Management.DataFactories.Core.IHubOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Hubs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Hubs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IHubOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-158">ハブを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-158">Operations for managing hubs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property LinkedServices As ILinkedServiceOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LinkedServices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-159">データ ファクトリの内部 linkedServices を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-159">Operations for managing data factory internal linkedServices.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-160">取得または長時間実行される操作の初期タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-160">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-161">取得または長時間実行される操作の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb27-161">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuth">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations OAuth { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations OAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.OAuth" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property OAuth As IOAuthOperations" />
      <MemberSignature Language="F#" Value="member this.OAuth : Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.OAuth" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.OAuth</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-162">OAuth 承認のための操作。</span><span class="sxs-lookup"><span data-stu-id="fdb27-162">Operations for OAuth authorizations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations Pipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Pipelines As IPipelineOperations" />
      <MemberSignature Language="F#" Value="member this.Pipelines : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClient.Pipelines" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Pipelines</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb27-163">パイプラインを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb27-163">Operations for managing pipelines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>