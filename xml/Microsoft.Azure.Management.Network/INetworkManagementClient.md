<Type Name="INetworkManagementClient" FullName="Microsoft.Azure.Management.Network.INetworkManagementClient">
  <TypeSignature Language="C#" Value="public interface INetworkManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.INetworkManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type INetworkManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="fd025-101">ネットワーク クライアント</span><span class="sxs-lookup"><span data-stu-id="fd025-101">Network Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd025-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IApplicationGatewaysOperations ApplicationGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations ApplicationGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ApplicationGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationGateways As IApplicationGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationGateways : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ApplicationGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IApplicationGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-103">IApplicationGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-103">Gets the IApplicationGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations ApplicationSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations ApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationSecurityGroups As IApplicationSecurityGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationSecurityGroups : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-104">IApplicationSecurityGroupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-104">Gets the IApplicationSecurityGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableEndpointServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations AvailableEndpointServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations AvailableEndpointServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.AvailableEndpointServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailableEndpointServices As IAvailableEndpointServicesOperations" />
      <MemberSignature Language="F#" Value="member this.AvailableEndpointServices : Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.AvailableEndpointServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-105">IAvailableEndpointServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-105">Gets the IAvailableEndpointServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-106">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="fd025-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpServiceCommunities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations BgpServiceCommunities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations BgpServiceCommunities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.BgpServiceCommunities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BgpServiceCommunities As IBgpServiceCommunitiesOperations" />
      <MemberSignature Language="F#" Value="member this.BgpServiceCommunities : Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.BgpServiceCommunities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-107">IBgpServiceCommunitiesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-107">Gets the IBgpServiceCommunitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckDnsNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;&gt; CheckDnsNameAvailabilityWithHttpMessagesAsync (string location, string domainNameLabel, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;&gt; CheckDnsNameAvailabilityWithHttpMessagesAsync(string location, string domainNameLabel, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkManagementClient.CheckDnsNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckDnsNameAvailabilityWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;&gt;" Usage="iNetworkManagementClient.CheckDnsNameAvailabilityWithHttpMessagesAsync (location, domainNameLabel, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="fd025-108">ドメイン名の場所です。</span><span class="sxs-lookup"><span data-stu-id="fd025-108">The location of the domain name.</span></span>
            </param>
        <param name="domainNameLabel">
            <span data-ttu-id="fd025-109">検証するドメイン名。</span><span class="sxs-lookup"><span data-stu-id="fd025-109">The domain name to be verified.</span></span> <span data-ttu-id="fd025-110">次の正規表現に従ってください: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$ です。</span><span class="sxs-lookup"><span data-stu-id="fd025-110">It must conform to the following regular expression: ^[a-z][a-z0-9-]{1,61}[a-z0-9]$.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd025-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd025-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd025-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd025-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd025-113">Cloudapp.azure.com ゾーンで、ドメイン名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="fd025-113">Checks whether a domain name in the cloudapp.azure.com zone is available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-114">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="fd025-114">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecurityRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations DefaultSecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations DefaultSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.DefaultSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecurityRules As IDefaultSecurityRulesOperations" />
      <MemberSignature Language="F#" Value="member this.DefaultSecurityRules : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.DefaultSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-115">IDefaultSecurityRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-115">Gets the IDefaultSecurityRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-116">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd025-116">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuitAuthorizations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations ExpressRouteCircuitAuthorizations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations ExpressRouteCircuitAuthorizations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuitAuthorizations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuitAuthorizations As IExpressRouteCircuitAuthorizationsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuitAuthorizations : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuitAuthorizations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-117">IExpressRouteCircuitAuthorizationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-117">Gets the IExpressRouteCircuitAuthorizationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuitPeerings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations ExpressRouteCircuitPeerings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations ExpressRouteCircuitPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuitPeerings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuitPeerings As IExpressRouteCircuitPeeringsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuitPeerings : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuitPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-118">IExpressRouteCircuitPeeringsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-118">Gets the IExpressRouteCircuitPeeringsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations ExpressRouteCircuits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations ExpressRouteCircuits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuits" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuits As IExpressRouteCircuitsOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuits : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteCircuits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-119">IExpressRouteCircuitsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-119">Gets the IExpressRouteCircuitsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteServiceProviders">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations ExpressRouteServiceProviders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations ExpressRouteServiceProviders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteServiceProviders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteServiceProviders As IExpressRouteServiceProvidersOperations" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteServiceProviders : Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.ExpressRouteServiceProviders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-120">IExpressRouteServiceProvidersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-120">Gets the IExpressRouteServiceProvidersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-121">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="fd025-121">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="fd025-122">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="fd025-122">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IInboundNatRulesOperations InboundNatRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IInboundNatRulesOperations InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InboundNatRules As IInboundNatRulesOperations" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : Microsoft.Azure.Management.Network.IInboundNatRulesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IInboundNatRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-123">IInboundNatRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-123">Gets the IInboundNatRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations LoadBalancerBackendAddressPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerBackendAddressPools As ILoadBalancerBackendAddressPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-124">ILoadBalancerBackendAddressPoolsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-124">Gets the ILoadBalancerBackendAddressPoolsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerFrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations LoadBalancerFrontendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations LoadBalancerFrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerFrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerFrontendIPConfigurations As ILoadBalancerFrontendIPConfigurationsOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerFrontendIPConfigurations : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerFrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-125">ILoadBalancerFrontendIPConfigurationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-125">Gets the ILoadBalancerFrontendIPConfigurationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerLoadBalancingRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations LoadBalancerLoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations LoadBalancerLoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerLoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerLoadBalancingRules As ILoadBalancerLoadBalancingRulesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerLoadBalancingRules : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerLoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-126">ILoadBalancerLoadBalancingRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-126">Gets the ILoadBalancerLoadBalancingRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerNetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations LoadBalancerNetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations LoadBalancerNetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerNetworkInterfaces As ILoadBalancerNetworkInterfacesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerNetworkInterfaces : Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerNetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-127">ILoadBalancerNetworkInterfacesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-127">Gets the ILoadBalancerNetworkInterfacesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations LoadBalancerProbes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations LoadBalancerProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerProbes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancerProbes As ILoadBalancerProbesOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerProbes : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancerProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-128">ILoadBalancerProbesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-128">Gets the ILoadBalancerProbesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILoadBalancersOperations LoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILoadBalancersOperations LoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancers As ILoadBalancersOperations" />
      <MemberSignature Language="F#" Value="member this.LoadBalancers : Microsoft.Azure.Management.Network.ILoadBalancersOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LoadBalancers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILoadBalancersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-129">ILoadBalancersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-129">Gets the ILoadBalancersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations LocalNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations LocalNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LocalNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalNetworkGateways As ILocalNetworkGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateways : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LocalNetworkGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-130">ILocalNetworkGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-130">Gets the ILocalNetworkGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-131">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="fd025-131">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="fd025-132">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="fd025-132">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIPConfigurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations NetworkInterfaceIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations NetworkInterfaceIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaceIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIPConfigurations As INetworkInterfaceIPConfigurationsOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIPConfigurations : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaceIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-133">INetworkInterfaceIPConfigurationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-133">Gets the INetworkInterfaceIPConfigurationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceLoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.INetworkInterfaceLoadBalancersOperations NetworkInterfaceLoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.INetworkInterfaceLoadBalancersOperations NetworkInterfaceLoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaceLoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceLoadBalancers As INetworkInterfaceLoadBalancersOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceLoadBalancers : Microsoft.Azure.Management.Network.INetworkInterfaceLoadBalancersOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaceLoadBalancers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.INetworkInterfaceLoadBalancersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-134">INetworkInterfaceLoadBalancersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-134">Gets the INetworkInterfaceLoadBalancersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.INetworkInterfacesOperations NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.INetworkInterfacesOperations NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As INetworkInterfacesOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : Microsoft.Azure.Management.Network.INetworkInterfacesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.INetworkInterfacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-135">INetworkInterfacesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-135">Gets the INetworkInterfacesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations NetworkSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations NetworkSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroups As INetworkSecurityGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroups : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-136">INetworkSecurityGroupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-136">Gets the INetworkSecurityGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWatchers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.INetworkWatchersOperations NetworkWatchers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.INetworkWatchersOperations NetworkWatchers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkWatchers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWatchers As INetworkWatchersOperations" />
      <MemberSignature Language="F#" Value="member this.NetworkWatchers : Microsoft.Azure.Management.Network.INetworkWatchersOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.NetworkWatchers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.INetworkWatchersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-137">INetworkWatchersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-137">Gets the INetworkWatchersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.Network.IOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-138">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-138">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptures">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IPacketCapturesOperations PacketCaptures { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IPacketCapturesOperations PacketCaptures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.PacketCaptures" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PacketCaptures As IPacketCapturesOperations" />
      <MemberSignature Language="F#" Value="member this.PacketCaptures : Microsoft.Azure.Management.Network.IPacketCapturesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.PacketCaptures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IPacketCapturesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-139">IPacketCapturesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-139">Gets the IPacketCapturesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddresses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IPublicIPAddressesOperations PublicIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations PublicIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.PublicIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddresses As IPublicIPAddressesOperations" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddresses : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.PublicIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IPublicIPAddressesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-140">IPublicIPAddressesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-140">Gets the IPublicIPAddressesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilterRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IRouteFilterRulesOperations RouteFilterRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations RouteFilterRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.RouteFilterRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteFilterRules As IRouteFilterRulesOperations" />
      <MemberSignature Language="F#" Value="member this.RouteFilterRules : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.RouteFilterRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IRouteFilterRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-141">IRouteFilterRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-141">Gets the IRouteFilterRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IRouteFiltersOperations RouteFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IRouteFiltersOperations RouteFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.RouteFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteFilters As IRouteFiltersOperations" />
      <MemberSignature Language="F#" Value="member this.RouteFilters : Microsoft.Azure.Management.Network.IRouteFiltersOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.RouteFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IRouteFiltersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-142">IRouteFiltersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-142">Gets the IRouteFiltersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IRoutesOperations Routes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IRoutesOperations Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.Routes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Routes As IRoutesOperations" />
      <MemberSignature Language="F#" Value="member this.Routes : Microsoft.Azure.Management.Network.IRoutesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IRoutesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-143">IRoutesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-143">Gets the IRoutesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTables">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IRouteTablesOperations RouteTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IRouteTablesOperations RouteTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.RouteTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteTables As IRouteTablesOperations" />
      <MemberSignature Language="F#" Value="member this.RouteTables : Microsoft.Azure.Management.Network.IRouteTablesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.RouteTables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IRouteTablesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-144">IRouteTablesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-144">Gets the IRouteTablesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ISecurityRulesOperations SecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ISecurityRulesOperations SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityRules As ISecurityRulesOperations" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : Microsoft.Azure.Management.Network.ISecurityRulesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ISecurityRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-145">ISecurityRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-145">Gets the ISecurityRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-146">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd025-146">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.ISubnetsOperations Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.ISubnetsOperations Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As ISubnetsOperations" />
      <MemberSignature Language="F#" Value="member this.Subnets : Microsoft.Azure.Management.Network.ISubnetsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.ISubnetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-147">ISubnetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-147">Gets the ISubnetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-148">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報。</span><span class="sxs-lookup"><span data-stu-id="fd025-148">The subscription credentials which uniquely identify the Microsoft Azure subscription.</span></span> <span data-ttu-id="fd025-149">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="fd025-149">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IUsagesOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IUsagesOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usages As IUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.Network.IUsagesOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.Usages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-150">IUsagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-150">Gets the IUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGatewayConnections">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations VirtualNetworkGatewayConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations VirtualNetworkGatewayConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkGatewayConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGatewayConnections As IVirtualNetworkGatewayConnectionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGatewayConnections : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkGatewayConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-151">IVirtualNetworkGatewayConnectionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-151">Gets the IVirtualNetworkGatewayConnectionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations VirtualNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations VirtualNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGateways As IVirtualNetworkGatewaysOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateways : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-152">IVirtualNetworkGatewaysOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-152">Gets the IVirtualNetworkGatewaysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations VirtualNetworkPeerings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkPeerings As IVirtualNetworkPeeringsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-153">IVirtualNetworkPeeringsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-153">Gets the IVirtualNetworkPeeringsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.IVirtualNetworksOperations VirtualNetworks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.IVirtualNetworksOperations VirtualNetworks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworks As IVirtualNetworksOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworks : Microsoft.Azure.Management.Network.IVirtualNetworksOperations" Usage="Microsoft.Azure.Management.Network.INetworkManagementClient.VirtualNetworks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.IVirtualNetworksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd025-154">IVirtualNetworksOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd025-154">Gets the IVirtualNetworksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>