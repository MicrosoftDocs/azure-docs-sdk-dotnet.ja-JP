<Type Name="BackupVaultServicesManagementClient" FullName="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient">
  <TypeSignature Language="C#" Value="public class BackupVaultServicesManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;, IDisposable, Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupVaultServicesManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; implements class Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupVaultServicesManagementClient&#xA;Inherits ServiceClient(Of BackupVaultServicesManagementClient)&#xA;Implements IBackupVaultServicesManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type BackupVaultServicesManagementClient = class&#xA;    inherit ServiceClient&lt;BackupVaultServicesManagementClient&gt;&#xA;    interface IBackupVaultServicesManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient</InterfaceName>
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
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-101">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-101">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="1ed30-102">必須。</span><span class="sxs-lookup"><span data-stu-id="1ed30-102">Required.</span></span> <span data-ttu-id="1ed30-103">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-103">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="1ed30-104">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-104">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-105">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-105">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="1ed30-106">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="1ed30-106">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-107">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-107">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="1ed30-108">必須。</span><span class="sxs-lookup"><span data-stu-id="1ed30-108">Required.</span></span> <span data-ttu-id="1ed30-109">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-109">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="1ed30-110">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-110">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="1ed30-111">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="1ed30-111">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-112">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-112">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="1ed30-113">必須。</span><span class="sxs-lookup"><span data-stu-id="1ed30-113">Required.</span></span> <span data-ttu-id="1ed30-114">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-114">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="1ed30-115">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-115">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="1ed30-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1ed30-116">Optional.</span></span> <span data-ttu-id="1ed30-117">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-117">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-118">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-118">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="1ed30-119">必須。</span><span class="sxs-lookup"><span data-stu-id="1ed30-119">Required.</span></span> <span data-ttu-id="1ed30-120">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-120">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="1ed30-121">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-121">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="1ed30-122">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1ed30-122">Optional.</span></span> <span data-ttu-id="1ed30-123">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-123">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="1ed30-124">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="1ed30-124">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-125">BackupVaultServicesManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-125">Initializes a new instance of the BackupVaultServicesManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-126">API のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-126">Gets the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-127">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-127">Gets the URI used as the base for all cloud service requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of BackupVaultServicesManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; -&gt; unit" Usage="backupVaultServicesManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="1ed30-128">複製する BackupVaultServicesManagementClient のインスタンス</span><span class="sxs-lookup"><span data-stu-id="1ed30-128">Instance of BackupVaultServicesManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ed30-129">現在のインスタンスから別の BackupVaultServicesManagementClient インスタンスにプロパティのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-129">Clones properties from current instance to another BackupVaultServicesManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IMarsContainerOperations Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Container" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Container As IMarsContainerOperations" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Container" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Container</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IMarsContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-130">Azure Backup の拡張機能のコンテナーの操作の定義。</span><span class="sxs-lookup"><span data-stu-id="1ed30-130">Definition of Container operations for the Azure Backup extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-131">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-131">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="1ed30-132">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-132">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-133">取得または長時間実行される操作の初期タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-133">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-134">取得または長時間実行される操作の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ed30-134">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vault">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IVaultOperations Vault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IVaultOperations Vault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Vault" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Vault As IVaultOperations" />
      <MemberSignature Language="F#" Value="member this.Vault : Microsoft.Azure.Management.BackupServices.IVaultOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Vault" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Vault</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IVaultOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed30-135">Azure Backup の拡張機能の資格情報コンテナーに関連する操作の定義。</span><span class="sxs-lookup"><span data-stu-id="1ed30-135">Definition of Vault-related operations for the Azure Backup extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>