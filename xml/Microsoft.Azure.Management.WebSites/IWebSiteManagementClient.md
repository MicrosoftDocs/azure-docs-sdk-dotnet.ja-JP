<Type Name="IWebSiteManagementClient" FullName="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient">
  <TypeSignature Language="C#" Value="public interface IWebSiteManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebSiteManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebSiteManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IWebSiteManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7301f-101">Web サイト管理クライアント</span><span class="sxs-lookup"><span data-stu-id="7301f-101">WebSite Management Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="7301f-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateOrders">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateOrders As IAppServiceCertificateOrdersOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateOrders : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-103">IAppServiceCertificateOrdersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-103">Gets the IAppServiceCertificateOrdersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceEnvironments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceEnvironments As IAppServiceEnvironmentsOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironments : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceEnvironments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-104">IAppServiceEnvironmentsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-104">Gets the IAppServiceEnvironmentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlans">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServicePlans" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServicePlans As IAppServicePlansOperations" />
      <MemberSignature Language="F#" Value="member this.AppServicePlans : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServicePlans" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServicePlansOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-105">IAppServicePlansOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-105">Gets the IAppServicePlansOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-106">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="7301f-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificates As ICertificatesOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.WebSites.ICertificatesOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ICertificatesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-107">ICertificatesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-107">Gets the ICertificatesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;" Usage="iWebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync (name, type, isFqdn, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="7301f-108">リソース名を確認してください。</span><span class="sxs-lookup"><span data-stu-id="7301f-108">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="7301f-109">リソースの種類の検証に使用します。</span><span class="sxs-lookup"><span data-stu-id="7301f-109">Resource type used for verification.</span></span> <span data-ttu-id="7301f-110">使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'</span><span class="sxs-lookup"><span data-stu-id="7301f-110">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="7301f-111">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="7301f-111">Is fully qualified domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-114">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="7301f-114">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-115">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="7301f-115">Check if a resource name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-116">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="7301f-116">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedWebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeletedWebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedWebApps As IDeletedWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.DeletedWebApps : Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeletedWebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-117">IDeletedWebAppsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-117">Gets the IDeletedWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-118">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7301f-118">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDomainsOperations Domains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDomainsOperations Domains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Domains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Domains As IDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.Domains : Microsoft.Azure.Management.WebSites.IDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Domains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-119">IDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-119">Gets the IDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-120">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="7301f-120">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="7301f-121">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7301f-121">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingUserWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="iWebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7301f-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-124">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="7301f-124">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-125">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="7301f-125">Gets publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync (string sourceControlType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync(string sourceControlType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSourceControlWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControlWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="iWebSiteManagementClient.GetSourceControlWithHttpMessagesAsync (sourceControlType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="7301f-126">ソース管理の種類</span><span class="sxs-lookup"><span data-stu-id="7301f-126">Type of source control</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-129">ソース管理のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-129">Gets source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-130">ソース管理のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-130">Gets source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSubscriptionDeploymentLocationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;" Usage="iWebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7301f-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-133">使用可能な地理的位置 plus ministamps の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-133">Gets list of available geo regions plus ministamps</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-134">使用可能な地理的位置 plus ministamps の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-134">Gets list of available geo regions plus ministamps</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7301f-135">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7301f-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-138">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-138">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-139">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-139">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync (string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync(string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync (sku, linuxWorkersEnabled, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sku">
            <span data-ttu-id="7301f-140">SKU の名前は、領域をフィルター処理に使用します。</span><span class="sxs-lookup"><span data-stu-id="7301f-140">Name of SKU used to filter the regions.</span></span> <span data-ttu-id="7301f-141">使用可能な値が含まれます: 'Free'、'Shared'、'Basic'、'Standard'、'Premium'、'PremiumV2'、'Dynamic'、'Isolated'</span><span class="sxs-lookup"><span data-stu-id="7301f-141">Possible values include: 'Free', 'Shared', 'Basic', 'Standard', 'Premium', 'PremiumV2', 'Dynamic', 'Isolated'</span></span>
            </param>
        <param name="linuxWorkersEnabled">
            <span data-ttu-id="7301f-142">指定&lt;コード&gt;true&lt;/code&gt; Linux ワーカーをサポートする領域だけにフィルターを適用する場合。</span><span class="sxs-lookup"><span data-stu-id="7301f-142">Specify &lt;code&gt;true&lt;/code&gt; if you want to filter to only regions that support Linux workers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-145">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-145">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-146">使用可能な地理的リージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-146">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7301f-147">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7301f-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-150">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-150">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-151">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-151">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7301f-152">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-152">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-154">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-154">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-155">すべてのプレミア アドオン プランを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-155">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSkusWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSkusWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;" Usage="iWebSiteManagementClient.ListSkusWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7301f-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-158">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-158">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-159">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7301f-159">List all SKUs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7301f-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7301f-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-163">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-163">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-164">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-164">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7301f-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-167">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-167">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-168">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-168">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-169">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="7301f-169">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="7301f-170">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="7301f-170">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.MoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebSiteManagementClient.MoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7301f-171">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7301f-171">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="7301f-172">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7301f-172">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-175">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="7301f-175">Move resources between resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-176">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="7301f-176">Move resources between resource groups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IProviderOperations Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IProviderOperations Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IProviderOperations" />
      <MemberSignature Language="F#" Value="member this.Provider : Microsoft.Azure.Management.WebSites.IProviderOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IProviderOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-177">IProviderOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-177">Gets the IProviderOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recommendations As IRecommendationsOperations" />
      <MemberSignature Language="F#" Value="member this.Recommendations : Microsoft.Azure.Management.WebSites.IRecommendationsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IRecommendationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-178">IRecommendationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-178">Gets the IRecommendationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-179">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7301f-179">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-180">Azure サブスクリプションの id。</span><span class="sxs-lookup"><span data-stu-id="7301f-180">Your Azure subscription ID.</span></span> <span data-ttu-id="7301f-181">これは、GUID 形式の文字列 (例: 00000000-0000-0000-0000-000000000000) です。</span><span class="sxs-lookup"><span data-stu-id="7301f-181">This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopLevelDomains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.TopLevelDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopLevelDomains As ITopLevelDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.TopLevelDomains : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.TopLevelDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-182">ITopLevelDomainsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-182">Gets the ITopLevelDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.User userDetails, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.User userDetails, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.User,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublishingUserWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.User * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="iWebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync (userDetails, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="userDetails">
            <span data-ttu-id="7301f-183">発行ユーザーの詳細</span><span class="sxs-lookup"><span data-stu-id="7301f-183">Details of publishing user</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-186">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="7301f-186">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-187">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="7301f-187">Updates publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync (string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync(string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSourceControlWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="iWebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync (sourceControlType, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="7301f-188">ソース管理の種類</span><span class="sxs-lookup"><span data-stu-id="7301f-188">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="7301f-189">ソース管理のトークンの情報</span><span class="sxs-lookup"><span data-stu-id="7301f-189">Source control token information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-192">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="7301f-192">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-193">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="7301f-193">Updates source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateMoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateMoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebSiteManagementClient.ValidateMoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7301f-194">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7301f-194">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="7301f-195">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7301f-195">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-198">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="7301f-198">Validate whether a resource can be moved.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-199">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="7301f-199">Validate whether a resource can be moved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;" Usage="iWebSiteManagementClient.ValidateWithHttpMessagesAsync (resourceGroupName, validateRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7301f-200">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7301f-200">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="7301f-201">検証する、リソースを持つ要求です。</span><span class="sxs-lookup"><span data-stu-id="7301f-201">Request with the resources to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-204">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="7301f-204">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-205">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="7301f-205">Validate if a resource can be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyHostingEnvironmentVnetWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;" Usage="iWebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="7301f-206">VNET について</span><span class="sxs-lookup"><span data-stu-id="7301f-206">VNET information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7301f-207">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7301f-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7301f-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7301f-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7301f-209">ネットワーク セキュリティ グループ ルールを分析して、この VNET が App Service 環境に互換性があることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7301f-209">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7301f-210">ネットワーク セキュリティ グループ ルールを分析して、この VNET が App Service 環境に互換性があることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7301f-210">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.WebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebApps As IWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.WebApps : Microsoft.Azure.Management.WebSites.IWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.WebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7301f-211">IWebAppsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7301f-211">Gets the IWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>