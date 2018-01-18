<Type Name="AutomationManagementClient" FullName="Microsoft.Azure.Management.Automation.AutomationManagementClient">
  <TypeSignature Language="C#" Value="public class AutomationManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Automation.IAutomationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutomationManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; implements class Microsoft.Azure.Management.Automation.IAutomationManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AutomationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class AutomationManagementClient&#xA;Inherits ServiceClient(Of AutomationManagementClient)&#xA;Implements IAutomationManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type AutomationManagementClient = class&#xA;    inherit ServiceClient&lt;AutomationManagementClient&gt;&#xA;    interface IAutomationManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Automation.AutomationManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Automation.IAutomationManagementClient</InterfaceName>
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
      <MemberSignature Language="C#" Value="public AutomationManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-101">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-101">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="ba2c6-102">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-102">Required.</span></span> <span data-ttu-id="ba2c6-103">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-103">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="ba2c6-104">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-104">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-105">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-105">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="ba2c6-106">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="ba2c6-106">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-107">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-107">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="ba2c6-108">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-108">Required.</span></span> <span data-ttu-id="ba2c6-109">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-109">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="ba2c6-110">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-110">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="ba2c6-111">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="ba2c6-111">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-112">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-112">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="ba2c6-113">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-113">Required.</span></span> <span data-ttu-id="ba2c6-114">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-114">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="ba2c6-115">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-115">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="ba2c6-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-116">Optional.</span></span> <span data-ttu-id="ba2c6-117">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-117">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-118">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-118">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="ba2c6-119">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-119">Required.</span></span> <span data-ttu-id="ba2c6-120">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-120">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="ba2c6-121">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-121">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="ba2c6-122">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-122">Optional.</span></span> <span data-ttu-id="ba2c6-123">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-123">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="ba2c6-124">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="ba2c6-124">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-125">AutomationManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-125">Initializes a new instance of the AutomationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IActivityOperations Activities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IActivityOperations Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Activities As IActivityOperations" />
      <MemberSignature Language="F#" Value="member this.Activities : Microsoft.Azure.Management.Automation.IActivityOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Activities" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Activities</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IActivityOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-126">Automation 活動をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-126">Service operation for automation activities.</span></span>  <span data-ttu-id="ba2c6-127">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-127">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentRegistrationInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.AgentRegistrationInformation" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property AgentRegistrationInformation As IAgentRegistrationOperation" />
      <MemberSignature Language="F#" Value="member this.AgentRegistrationInformation : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.AgentRegistrationInformation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AgentRegistrationInformation</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAgentRegistrationOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-128">自動化エージェント登録情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-128">Service operation for automation agent registration information.</span></span>
            <span data-ttu-id="ba2c6-129">(詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-129">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-130">API のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-130">Gets the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutomationAccounts">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.AutomationAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property AutomationAccounts As IAutomationAccountOperations" />
      <MemberSignature Language="F#" Value="member this.AutomationAccounts : Microsoft.Azure.Management.Automation.IAutomationAccountOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.AutomationAccounts" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AutomationAccounts</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAutomationAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-131">オートメーション アカウントのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-131">Service operation for automation accounts.</span></span>  <span data-ttu-id="ba2c6-132">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-132">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-133">すべてのクラウド サービス要求のベースとして使用する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-133">Gets the URI used as the base for all cloud service requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ICertificateOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICertificateOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Certificates As ICertificateOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.Automation.ICertificateOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Certificates</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-134">オートメーションの証明書をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-134">Service operation for automation certificates.</span></span>  <span data-ttu-id="ba2c6-135">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-135">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.Automation.AutomationManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of AutomationManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; -&gt; unit" Usage="automationManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="ba2c6-136">AutomationManagementClient を複製するのインスタンス</span><span class="sxs-lookup"><span data-stu-id="ba2c6-136">Instance of AutomationManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-137">現在のインスタンスから別の AutomationManagementClient インスタンスにプロパティのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-137">Clones properties from current instance to another AutomationManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationJobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.CompilationJobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property CompilationJobs As IDscCompilationJobOperations" />
      <MemberSignature Language="F#" Value="member this.CompilationJobs : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.CompilationJobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.CompilationJobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscCompilationJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-138">Automation dsc 構成のサービスの操作は、ジョブをコンパイルします。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-138">Service operation for automation dsc configuration compile jobs.</span></span>
            <span data-ttu-id="ba2c6-139">(詳細については http://aka.ms/azureautomationsdk/dscccompilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-139">(see http://aka.ms/azureautomationsdk/dscccompilationjoboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configurations">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Configurations" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Configurations As IDscConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.Configurations : Microsoft.Azure.Management.Automation.IDscConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Configurations" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Configurations</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-140">構成のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-140">Service operation for configurations.</span></span>  <span data-ttu-id="ba2c6-141">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-141">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connections">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IConnectionOperations Connections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionOperations Connections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Connections" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Connections As IConnectionOperations" />
      <MemberSignature Language="F#" Value="member this.Connections : Microsoft.Azure.Management.Automation.IConnectionOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Connections" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Connections</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-142">オートメーション接続のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-142">Service operation for automation connections.</span></span>  <span data-ttu-id="ba2c6-143">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-143">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ConnectionTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ConnectionTypes As IConnectionTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ConnectionTypes : Microsoft.Azure.Management.Automation.IConnectionTypeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ConnectionTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ConnectionTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-144">オートメーション connectiontypes のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-144">Service operation for automation connectiontypes.</span></span>  <span data-ttu-id="ba2c6-145">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-145">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationTokenHandler&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.List&lt;T&gt; ContinuationTokenHandler&lt;T&gt; (Func&lt;string,Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;T&gt;&gt; listFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.List`1&lt;!!T&gt; ContinuationTokenHandler&lt;T&gt;(class System.Func`2&lt;string, class Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1&lt;!!T&gt;&gt; listFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.ContinuationTokenHandler``1(System.Func{System.String,Microsoft.Azure.Management.Automation.ResponseWithSkipToken{``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ContinuationTokenHandler(Of T) (listFunc As Func(Of String, ResponseWithSkipToken(Of T))) As List(Of T)" />
      <MemberSignature Language="F#" Value="static member ContinuationTokenHandler : Func&lt;string, Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt;&gt; -&gt; System.Collections.Generic.List&lt;'T&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ContinuationTokenHandler listFunc" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="listFunc" Type="System.Func&lt;System.String,Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;T&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="listFunc">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-146">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-146">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="ba2c6-147">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-147">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationResultStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.GetOperationResultStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationResultStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;&#xA;override this.GetOperationResultStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="automationManagementClient.GetOperationResultStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationResultStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Automation.AutomationManagementClient/&lt;GetOperationResultStatusAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="ba2c6-148">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-148">Required.</span></span> <span data-ttu-id="ba2c6-149">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-149">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba2c6-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-150">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-151">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-151">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="ba2c6-152">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-152">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ba2c6-153">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-153">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync (string requestId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync(string requestId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;&#xA;override this.GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;" Usage="automationManagementClient.GetOperationStatusAsync (requestId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Automation.AutomationManagementClient/&lt;GetOperationStatusAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestId">
            <span data-ttu-id="ba2c6-154">必須。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-154">Required.</span></span> <span data-ttu-id="ba2c6-155">追跡する要求の要求 ID。要求 ID は、すべての要求に対して x ms 要求 id の応答ヘッダーで返されます。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-155">The request ID for the request you wish to track. The request ID is returned in the x-ms-request-id response header for every request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba2c6-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-156">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba2c6-157">Get Operation Status 操作には、指定された操作のステータスが返されます。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-157">The Get Operation Status operation returns the status of thespecified operation.</span></span> <span data-ttu-id="ba2c6-158">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-158">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>  <span data-ttu-id="ba2c6-159">(詳細については http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-159">(see http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ba2c6-160">応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-160">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is inprogress, or has failed.</span></span> <span data-ttu-id="ba2c6-161">この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-161">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span>  <span data-ttu-id="ba2c6-162">非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-162">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span>  <span data-ttu-id="ba2c6-163">非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-163">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request, and also includes error information regarding the failure.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridRunbookWorkerGroups">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property HybridRunbookWorkerGroups As IHybridRunbookWorkerGroupOperations" />
      <MemberSignature Language="F#" Value="member this.HybridRunbookWorkerGroups : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.HybridRunbookWorkerGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-164">Automation hybrid runbook worker グループのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-164">Service operation for automation hybrid runbook worker group.</span></span>  <span data-ttu-id="ba2c6-165">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-165">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Jobs As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.Automation.IJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Jobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Jobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-166">オートメーション ジョブのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-166">Service operation for automation jobs.</span></span>  <span data-ttu-id="ba2c6-167">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-167">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSchedules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.JobSchedules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property JobSchedules As IJobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobSchedules : Microsoft.Azure.Management.Automation.IJobScheduleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.JobSchedules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobSchedules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-168">Automation ジョブ スケジュールのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-168">Service operation for automation job schedules.</span></span>  <span data-ttu-id="ba2c6-169">(詳細については http://aka.ms/azureautomationsdk/jobscheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-169">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobStreams">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.JobStreams" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property JobStreams As IJobStreamOperations" />
      <MemberSignature Language="F#" Value="member this.JobStreams : Microsoft.Azure.Management.Automation.IJobStreamOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.JobStreams" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobStreams</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobStreamOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-170">Automation ジョブ ストリームのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-170">Service operation for automation job streams.</span></span>  <span data-ttu-id="ba2c6-171">(詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-171">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-172">取得または長時間実行される操作の初期タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-172">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-173">取得または長時間実行される操作の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-173">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Modules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IModuleOperations Modules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IModuleOperations Modules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Modules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Modules As IModuleOperations" />
      <MemberSignature Language="F#" Value="member this.Modules : Microsoft.Azure.Management.Automation.IModuleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Modules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Modules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IModuleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-174">オートメーション モジュールをサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-174">Service operation for automation modules.</span></span>  <span data-ttu-id="ba2c6-175">(詳細については http://aka.ms/azureautomationsdk/moduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-175">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeConfigurations">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property NodeConfigurations As IDscNodeConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.NodeConfigurations : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeConfigurations" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeConfigurations</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-176">Automation dsc ノード構成のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-176">Service operation for automation dsc node configurations.</span></span>  <span data-ttu-id="ba2c6-177">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-177">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReports">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeReports" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property NodeReports As IDscNodeReportsOperations" />
      <MemberSignature Language="F#" Value="member this.NodeReports : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeReports" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeReports</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeReportsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-178">サービスのノードのレポートを操作します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-178">Service operation for node reports.</span></span>  <span data-ttu-id="ba2c6-179">(詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-179">(see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Nodes As IDscNodeOperations" />
      <MemberSignature Language="F#" Value="member this.Nodes : Microsoft.Azure.Management.Automation.IDscNodeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Nodes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Nodes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-180">Dsc ノードのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-180">Service operation for dsc nodes.</span></span>  <span data-ttu-id="ba2c6-181">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-181">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectDataTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ObjectDataTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ObjectDataTypes As IObjectDataTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ObjectDataTypes : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ObjectDataTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ObjectDataTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IObjectDataTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-182">オートメーション オブジェクトのデータ型のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-182">Service operation for automation object data types.</span></span>  <span data-ttu-id="ba2c6-183">(詳細については http://aka.ms/azureautomationsdk/objectdatatypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-183">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PsCredentials">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.PsCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property PsCredentials As ICredentialOperations" />
      <MemberSignature Language="F#" Value="member this.PsCredentials : Microsoft.Azure.Management.Automation.ICredentialOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.PsCredentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.PsCredentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICredentialOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-184">Automation の資格情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-184">Service operation for automation credentials.</span></span>  <span data-ttu-id="ba2c6-185">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-185">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNamespace">
      <MemberSignature Language="C#" Value="public string ResourceNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ResourceNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceNamespace : string with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ResourceNamespace" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ResourceNamespace</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-186">取得またはリソースの名前空間を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-186">Gets or sets the resource namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookDraft">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.RunbookDraft" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property RunbookDraft As IRunbookDraftOperations" />
      <MemberSignature Language="F#" Value="member this.RunbookDraft : Microsoft.Azure.Management.Automation.IRunbookDraftOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.RunbookDraft" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.RunbookDraft</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookDraftOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-187">Automation runbook の下書きのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-187">Service operation for automation runbook draft.</span></span>  <span data-ttu-id="ba2c6-188">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-188">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbooks">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Runbooks" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Runbooks As IRunbookOperations" />
      <MemberSignature Language="F#" Value="member this.Runbooks : Microsoft.Azure.Management.Automation.IRunbookOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Runbooks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Runbooks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-189">Automation の runbook のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-189">Service operation for automation runbooks.</span></span>  <span data-ttu-id="ba2c6-190">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-190">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IScheduleOperations Schedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IScheduleOperations Schedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Schedules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Schedules As IScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.Schedules : Microsoft.Azure.Management.Automation.IScheduleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Schedules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Schedules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-191">Automation のスケジュールのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-191">Service operation for automation schedules.</span></span>  <span data-ttu-id="ba2c6-192">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-192">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Statistics As IStatisticsOperations" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Management.Automation.IStatisticsOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Statistics" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Statistics</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IStatisticsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-193">オートメーションの統計情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-193">Service operation for automation statistics.</span></span>  <span data-ttu-id="ba2c6-194">(詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-194">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestJobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.TestJobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TestJobs As ITestJobOperations" />
      <MemberSignature Language="F#" Value="member this.TestJobs : Microsoft.Azure.Management.Automation.ITestJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.TestJobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TestJobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITestJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-195">オートメーションのテスト ジョブのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-195">Service operation for automation test jobs.</span></span>  <span data-ttu-id="ba2c6-196">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-196">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeFields">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.TypeFields" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TypeFields As ITypeFieldOperations" />
      <MemberSignature Language="F#" Value="member this.TypeFields : Microsoft.Azure.Management.Automation.ITypeFieldOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.TypeFields" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TypeFields</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITypeFieldOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-197">オートメーション型のフィールドのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-197">Service operation for automation type fields.</span></span>  <span data-ttu-id="ba2c6-198">(詳細については http://aka.ms/azureautomationsdk/typefieldoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-198">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IUsageOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IUsageOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Usages As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.Automation.IUsageOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Usages" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Usages</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-199">オートメーションの使用時にサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-199">Service operation for automation usages.</span></span>  <span data-ttu-id="ba2c6-200">(詳細については http://aka.ms/azureautomationsdk/usageoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-200">(see http://aka.ms/azureautomationsdk/usageoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Variables">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IVariableOperations Variables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IVariableOperations Variables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Variables" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Variables As IVariableOperations" />
      <MemberSignature Language="F#" Value="member this.Variables : Microsoft.Azure.Management.Automation.IVariableOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Variables" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Variables</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IVariableOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-201">オートメーション変数のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-201">Service operation for automation variables.</span></span>  <span data-ttu-id="ba2c6-202">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-202">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Webhooks">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Webhooks" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Webhooks As IWebhookOperations" />
      <MemberSignature Language="F#" Value="member this.Webhooks : Microsoft.Azure.Management.Automation.IWebhookOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Webhooks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Webhooks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IWebhookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba2c6-203">Automation webhook のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ba2c6-203">Service operation for automation webhook.</span></span>  <span data-ttu-id="ba2c6-204">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ba2c6-204">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>