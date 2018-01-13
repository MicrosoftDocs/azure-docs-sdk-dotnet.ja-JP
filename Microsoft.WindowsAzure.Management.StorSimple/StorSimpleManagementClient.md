<Type Name="StorSimpleManagementClient" FullName="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient">
  <TypeSignature Language="C#" Value="public class StorSimpleManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt;, IDisposable, Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorSimpleManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt; implements class Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class StorSimpleManagementClient&#xA;Inherits ServiceClient(Of StorSimpleManagementClient)&#xA;Implements IDisposable, IStorSimpleManagementClient" />
  <TypeSignature Language="F#" Value="type StorSimpleManagementClient = class&#xA;    inherit ServiceClient&lt;StorSimpleManagementClient&gt;&#xA;    interface IStorSimpleManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="36532-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="36532-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36532-102">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-102">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" Usage="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="36532-103">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="36532-103">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-104">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-104">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient (string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (cloudServiceName As String, resourceName As String, resourceId As String, resourceNamespace As String, credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient : string * string * string * string * Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" Usage="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient (cloudServiceName, resourceName, resourceId, resourceNamespace, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceNamespace" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="cloudServiceName">
            <span data-ttu-id="36532-105">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-105">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="36532-106">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-106">Required.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="36532-107">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-107">Required.</span></span>
            </param>
        <param name="resourceNamespace">
            <span data-ttu-id="36532-108">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-108">Required.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="36532-109">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-109">Required.</span></span> <span data-ttu-id="36532-110">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-110">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="36532-111">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="36532-111">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-112">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-112">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient (string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient : string * string * string * string * Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" Usage="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient (cloudServiceName, resourceName, resourceId, resourceNamespace, credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceNamespace" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="cloudServiceName">
            <span data-ttu-id="36532-113">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="36532-114">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-114">Required.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="36532-115">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-115">Required.</span></span>
            </param>
        <param name="resourceNamespace">
            <span data-ttu-id="36532-116">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-116">Required.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="36532-117">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-117">Required.</span></span> <span data-ttu-id="36532-118">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-118">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="36532-119">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="36532-119">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="36532-120">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="36532-120">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-121">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-121">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient (string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (cloudServiceName As String, resourceName As String, resourceId As String, resourceNamespace As String, credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient : string * string * string * string * Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" Usage="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient (cloudServiceName, resourceName, resourceId, resourceNamespace, credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceNamespace" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="cloudServiceName">
            <span data-ttu-id="36532-122">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-122">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="36532-123">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-123">Required.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="36532-124">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-124">Required.</span></span>
            </param>
        <param name="resourceNamespace">
            <span data-ttu-id="36532-125">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-125">Required.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="36532-126">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-126">Required.</span></span> <span data-ttu-id="36532-127">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-127">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="36532-128">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="36532-128">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="36532-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="36532-129">Optional.</span></span> <span data-ttu-id="36532-130">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-130">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-131">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-131">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorSimpleManagementClient (string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string cloudServiceName, string resourceName, string resourceId, string resourceNamespace, class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient : string * string * string * string * Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient" Usage="new Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient (cloudServiceName, resourceName, resourceId, resourceNamespace, credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceNamespace" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="cloudServiceName">
            <span data-ttu-id="36532-132">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-132">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="36532-133">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-133">Required.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="36532-134">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-134">Required.</span></span>
            </param>
        <param name="resourceNamespace">
            <span data-ttu-id="36532-135">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-135">Required.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="36532-136">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-136">Required.</span></span> <span data-ttu-id="36532-137">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-137">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="36532-138">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="36532-138">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="36532-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="36532-139">Optional.</span></span> <span data-ttu-id="36532-140">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-140">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="36532-141">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="36532-141">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-142">StorSimpleManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36532-142">Initializes a new instance of the StorSimpleManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-143">API のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-143">Gets the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations Backup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations Backup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Backup" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Backup As IBackupOperations" />
      <MemberSignature Language="F#" Value="member this.Backup : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Backup" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Backup</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-144">バックアップに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-144">All Operations related to Backup</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations BackupPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations BackupPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.BackupPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BackupPolicy As IBackupPolicyOperations" />
      <MemberSignature Language="F#" Value="member this.BackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.BackupPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BackupPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-145">バックアップ ポリシーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-145">All Operations related to Backup policies</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-146">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-146">Gets the URI used as the base for all cloud service requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of StorSimpleManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt; -&gt; unit" Usage="storSimpleManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="36532-147">複製する StorSimpleManagementClient のインスタンス</span><span class="sxs-lookup"><span data-stu-id="36532-147">Instance of StorSimpleManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-148">現在のインスタンスから別の StorSimpleManagementClient インスタンスにプロパティのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="36532-148">Clones properties from current instance to another StorSimpleManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneVolume">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations CloneVolume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations CloneVolume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.CloneVolume" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property CloneVolume As ICloneVolumeOperations" />
      <MemberSignature Language="F#" Value="member this.CloneVolume : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.CloneVolume" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloneVolume</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-149">CloneVolume に関連するすべての操作 (詳細については http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx を参照してください)</span><span class="sxs-lookup"><span data-stu-id="36532-149">All Operations related to CloneVolume  (see http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceName">
      <MemberSignature Language="C#" Value="public string CloudServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.CloudServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceName As String" />
      <MemberSignature Language="F#" Value="member this.CloudServiceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.CloudServiceName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloudServiceName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-150">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36532-150">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="36532-151">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="36532-151">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations DataContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations DataContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DataContainer" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DataContainer As IDataContainerOperations" />
      <MemberSignature Language="F#" Value="member this.DataContainer : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DataContainer" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DataContainer</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-152">ボリューム コンテナーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-152">All Operations related to Volume Containers</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceDetails">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations DeviceDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations DeviceDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceDetails" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DeviceDetails As IDeviceDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceDetails" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceDetails</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-153">デバイスの詳細に関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-153">All Operations related to Device Details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceFailover">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations DeviceFailover { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations DeviceFailover" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceFailover" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DeviceFailover As IDeviceFailoverOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceFailover : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceFailover" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceFailover</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-154">デバイスのフェールオーバーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-154">All Operations related to Device Failover</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceJob">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations DeviceJob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations DeviceJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceJob" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DeviceJob As IDeviceJobOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DeviceJob" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceJob</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-155">デバイスのジョブに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-155">All Operations related to Device Jobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DevicePublicKey">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations DevicePublicKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations DevicePublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DevicePublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DevicePublicKey As IDevicePublicKeyOperations" />
      <MemberSignature Language="F#" Value="member this.DevicePublicKey : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.DevicePublicKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DevicePublicKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-156">デバイスの公開キーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-156">All Operations related to Device Public keys</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Devices">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations Devices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations Devices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Devices" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Devices As IDeviceOperations" />
      <MemberSignature Language="F#" Value="member this.Devices : Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.Devices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Devices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-157">デバイスに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-157">All Operations related to Devices</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync (string taskId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync(string taskId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;&#xA;override this.GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="storSimpleManagementClient.GetOperationStatusAsync (taskId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient/&lt;GetOperationStatusAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskId">
            <span data-ttu-id="36532-158">必須。</span><span class="sxs-lookup"><span data-stu-id="36532-158">Required.</span></span> <span data-ttu-id="36532-159">タスク Id を要求する追跡できます。</span><span class="sxs-lookup"><span data-stu-id="36532-159">The task Id for the request you wish to track.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36532-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36532-160">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36532-161">タスクの状態の取得では、指定されたタスク id の状態を返します。非同期タスクを呼び出した後は、呼び出すことができます、タスクが成功したかどうかを決定するタスクの状態の取得に失敗しました。 または、進行中です。</span><span class="sxs-lookup"><span data-stu-id="36532-161">The Get Task Status returns the status of the specified task id. After calling an asynchronous task, you can call Get Task Status to determine whether the task has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36532-162">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="36532-162">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IscsiConnection">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations IscsiConnection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations IscsiConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.IscsiConnection" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property IscsiConnection As IIscsiConnectionDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.IscsiConnection : Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.IscsiConnection" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.IscsiConnection</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-163">Iscsi 接続に関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-163">All Operations related to iscsi connection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-164">取得または長時間実行される操作の初期タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="36532-164">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-165">取得または長時間実行される操作の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="36532-165">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrateLegacyAppliance">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations MigrateLegacyAppliance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations MigrateLegacyAppliance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.MigrateLegacyAppliance" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property MigrateLegacyAppliance As IMigrationOperations" />
      <MemberSignature Language="F#" Value="member this.MigrateLegacyAppliance : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.MigrateLegacyAppliance" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.MigrateLegacyAppliance</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-166">レガシ アプライアンスの移行</span><span class="sxs-lookup"><span data-stu-id="36532-166">Migration of Legacy Appliance</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceEncryptionKeys">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations ResourceEncryptionKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations ResourceEncryptionKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceEncryptionKeys" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ResourceEncryptionKeys As IResourceEncryptionKeyOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceEncryptionKeys : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceEncryptionKeys" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceEncryptionKeys</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-167">暗号化キーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-167">All Operations related to Crypto keys</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNamespace">
      <MemberSignature Language="C#" Value="public string ResourceNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceNamespace : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ResourceNamespace" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceNamespace</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceConfig">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations ServiceConfig { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations ServiceConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ServiceConfig" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ServiceConfig As IServiceConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceConfig : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.ServiceConfig" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ServiceConfig</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-168">サービス構成に関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-168">All Operations related to Service configurations</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDevice">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations VirtualDevice { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations VirtualDevice" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.VirtualDevice" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property VirtualDevice As IVirtualDeviceOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualDevice : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.VirtualDevice" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDevice</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-169">仮想デバイスに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-169">All Operations related to Virtual Device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDisk">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations VirtualDisk { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations VirtualDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.VirtualDisk" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property VirtualDisk As IVirtualDiskOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualDisk : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClient.VirtualDisk" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDisk</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36532-170">仮想ディスクに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="36532-170">All Operations related to virtual disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>