<Type Name="ICdnManagementClient" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient">
  <TypeSignature Language="C#" Value="public interface ICdnManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICdnManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICdnManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ICdnManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="57027-101">これらの Api を使用すると、Azure リソース マネージャーを通して Azure CDN のリソースを管理できます。</span><span class="sxs-lookup"><span data-stu-id="57027-101">Use these APIs to manage Azure CDN resources through the Azure Resource Manager.</span></span> <span data-ttu-id="57027-102">これらのリソースへの要求が安全であることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="57027-102">You must make sure that requests made to these resources are secure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-103">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="57027-103">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-104">クライアント要求で使用する API のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="57027-104">Version of the API to be used with the client request.</span></span> <span data-ttu-id="57027-105">現在のバージョンは、2016-10-02 です。</span><span class="sxs-lookup"><span data-stu-id="57027-105">Current version is 2016-10-02.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-106">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="57027-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt;" Usage="iCdnManagementClient.CheckNameAvailabilityWithHttpMessagesAsync (name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="57027-107">検証対象のリソース名。</span><span class="sxs-lookup"><span data-stu-id="57027-107">The resource name to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="57027-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="57027-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57027-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="57027-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57027-110">リソース名の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="57027-110">Check the availability of a resource name.</span></span> <span data-ttu-id="57027-111">CDN エンドポイントなど、グローバルに一意な名前のリソースに必要です。</span><span class="sxs-lookup"><span data-stu-id="57027-111">This is needed for resources where name is globally unique, such as a CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-112">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="57027-112">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations CustomDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations CustomDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.CustomDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomains As ICustomDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.CustomDomains : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.CustomDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-113">ICustomDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="57027-113">Gets the ICustomDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-114">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="57027-114">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations EdgeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations EdgeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.EdgeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EdgeNodes As IEdgeNodesOperations" />
      <MemberSignature Language="F#" Value="member this.EdgeNodes : Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.EdgeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IEdgeNodesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-115">IEdgeNodesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="57027-115">Gets the IEdgeNodesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As IEndpointsOperations" />
      <MemberSignature Language="F#" Value="member this.Endpoints : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-116">IEndpointsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="57027-116">Gets the IEndpointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-117">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="57027-117">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="57027-118">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="57027-118">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListOperationsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOperationsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;" Usage="iCdnManagementClient.ListOperationsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="57027-119">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="57027-119">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="57027-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="57027-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57027-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="57027-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57027-122">すべての利用可能な CDN の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="57027-122">Lists all of the available CDN REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListOperationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOperationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;" Usage="iCdnManagementClient.ListOperationsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="57027-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="57027-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57027-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="57027-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57027-125">すべての利用可能な CDN の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="57027-125">Lists all of the available CDN REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListResourceUsageNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="iCdnManagementClient.ListResourceUsageNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="57027-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="57027-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="57027-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="57027-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57027-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="57027-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57027-129">クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。</span><span class="sxs-lookup"><span data-stu-id="57027-129">Check the quota and actual usage of the CDN profiles under the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.ListResourceUsageWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="iCdnManagementClient.ListResourceUsageWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="57027-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="57027-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57027-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="57027-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57027-132">クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。</span><span class="sxs-lookup"><span data-stu-id="57027-132">Check the quota and actual usage of the CDN profiles under the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-133">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="57027-133">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="57027-134">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="57027-134">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origins">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations Origins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations Origins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Origins" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origins As IOriginsOperations" />
      <MemberSignature Language="F#" Value="member this.Origins : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Origins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-135">IOriginsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="57027-135">Gets the IOriginsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Profiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations Profiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations Profiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Profiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Profiles As IProfilesOperations" />
      <MemberSignature Language="F#" Value="member this.Profiles : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.Profiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-136">IProfilesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="57027-136">Gets the IProfilesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-137">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="57027-137">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57027-138">Azure サブスクリプション ID。</span><span class="sxs-lookup"><span data-stu-id="57027-138">Azure Subscription ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>