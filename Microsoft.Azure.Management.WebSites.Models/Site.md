<Type Name="Site" FullName="Microsoft.Azure.Management.WebSites.Models.Site">
  <TypeSignature Language="C#" Value="public class Site : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Site extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Site" />
  <TypeSignature Language="VB.NET" Value="Public Class Site&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Site = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1b4cd-101">Web アプリ、モバイル アプリ バックエンドでは、または API アプリ。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-101">A web app, a mobile app backend, or an API app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Site ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-102">サイトのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-102">Initializes a new instance of the Site class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Site (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, string possibleOutboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo = null, Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus = null, Nullable&lt;bool&gt; httpsOnly = null, Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, string possibleOutboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo, class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus, valuetype System.Nullable`1&lt;bool&gt; httpsOnly, class Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.WebSites.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.WebSites.Models.CloningInfo,Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus,System.Nullable{System.Boolean},Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Site : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.WebSites.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.WebSites.Models.CloningInfo * Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus * Nullable&lt;bool&gt; * Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity -&gt; Microsoft.Azure.Management.WebSites.Models.Site" Usage="new Microsoft.Azure.Management.WebSites.Models.Site (location, id, name, kind, type, tags, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, possibleOutboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, snapshotInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus, httpsOnly, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.WebSites.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="possibleOutboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.WebSites.Models.CloningInfo" />
        <Parameter Name="snapshotInfo" Type="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" />
        <Parameter Name="httpsOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="1b4cd-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="1b4cd-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="1b4cd-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="1b4cd-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="1b4cd-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="1b4cd-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-108">Resource tags.</span></span></param>
        <param name="state"><span data-ttu-id="1b4cd-109">アプリの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-109">Current state of the app.</span></span></param>
        <param name="hostNames"><span data-ttu-id="1b4cd-110">アプリに関連付けられているホスト名です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-110">Hostnames associated with the app.</span></span></param>
        <param name="repositorySiteName"><span data-ttu-id="1b4cd-111">リポジトリ サイトの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-111">Name of the repository site.</span></span></param>
        <param name="usageState"><span data-ttu-id="1b4cd-112">アプリでのクォータ使用率が超過するかどうかを示す状態です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-112">State indicating whether the app has exceeded its quota usage.</span></span> <span data-ttu-id="1b4cd-113">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-113">Read-only.</span></span> <span data-ttu-id="1b4cd-114">使用可能な値が含まれます: 'Normal'、'を超えました'</span><span class="sxs-lookup"><span data-stu-id="1b4cd-114">Possible values include: 'Normal', 'Exceeded'</span></span></param>
        <param name="enabled"><span data-ttu-id="1b4cd-115">&lt;コード&gt;true&lt;/code&gt; 、アプリが有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-115">&lt;code&gt;true&lt;/code&gt; if the app is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="1b4cd-116">この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-116">Setting this value to false disables the app (takes the app offline).</span></span></param>
        <param name="enabledHostNames"><span data-ttu-id="1b4cd-117">アプリの有効なホスト名です。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-117">Enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span>
            <span data-ttu-id="1b4cd-118">それ以外の場合、アプリは、そのホスト名では処理できません。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-118">Otherwise, the app is not served on those hostnames.</span></span></param>
        <param name="availabilityState"><span data-ttu-id="1b4cd-119">アプリの管理情報の可用性の状態。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-119">Management information availability state for the app.</span></span> <span data-ttu-id="1b4cd-120">使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'</span><span class="sxs-lookup"><span data-stu-id="1b4cd-120">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span></param>
        <param name="hostNameSslStates"><span data-ttu-id="1b4cd-121">ホスト名の SSL の状態は、アプリのホスト名の SSL バインドの管理に使用されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-121">Hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="1b4cd-122">リソース ID、関連付けられている App Service プランの設定として書式設定:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-122">Resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span></param>
        <param name="reserved"><span data-ttu-id="1b4cd-123">&lt;コード&gt;true&lt;/code&gt;予約されている場合は、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-123">&lt;code&gt;true&lt;/code&gt; if reserved; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="lastModifiedTimeUtc"><span data-ttu-id="1b4cd-124">最後の時刻 (utc) で、アプリが変更されました。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-124">Last time the app was modified, in UTC.</span></span> <span data-ttu-id="1b4cd-125">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-125">Read-only.</span></span></param>
        <param name="siteConfig"><span data-ttu-id="1b4cd-126">アプリの構成。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-126">Configuration of the app.</span></span></param>
        <param name="trafficManagerHostNames"><span data-ttu-id="1b4cd-127">Azure Traffic Manager のホスト名は、アプリに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-127">Azure Traffic Manager hostnames associated with the app.</span></span> <span data-ttu-id="1b4cd-128">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-128">Read-only.</span></span></param>
        <param name="scmSiteAlsoStopped"><span data-ttu-id="1b4cd-129">&lt;コード&gt;true&lt;/code&gt; 、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-129">&lt;code&gt;true&lt;/code&gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="1b4cd-130">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-130">The default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="targetSwapSlot"><span data-ttu-id="1b4cd-131">このアプリにスワップは展開スロットを指定します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-131">Specifies which deployment slot this app will swap into.</span></span> <span data-ttu-id="1b4cd-132">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-132">Read-only.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="1b4cd-133">アプリの使用を app Service 環境。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-133">App Service Environment to use for the app.</span></span></param>
        <param name="clientAffinityEnabled"><span data-ttu-id="1b4cd-134">&lt;コード&gt;true&lt;/code&gt;クライアントのアフィニティを有効にするには&lt;コード&gt;false&lt;/code&gt;セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-134">&lt;code&gt;true&lt;/code&gt; to enable client affinity; &lt;code&gt;false&lt;/code&gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="1b4cd-135">既定値は&lt;コード&gt;true&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-135">Default is &lt;code&gt;true&lt;/code&gt;.</span></span></param>
        <param name="clientCertEnabled"><span data-ttu-id="1b4cd-136">&lt;コード&gt;true&lt;/code&gt; (TLS の相互認証) です。 クライアント証明書認証を有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-136">&lt;code&gt;true&lt;/code&gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="1b4cd-137">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-137">Default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostNamesDisabled"><span data-ttu-id="1b4cd-138">&lt;コード&gt;true&lt;/code&gt; ; アプリのパブリック ホスト名を無効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-138">&lt;code&gt;true&lt;/code&gt; to disable the public hostnames of the app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span>
            <span data-ttu-id="1b4cd-139">場合&lt;コード&gt;true&lt;/code&gt;アプリは API 管理プロセスを使用してアクセスできるのみです。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-139">If &lt;code&gt;true&lt;/code&gt;, the app is only accessible via API management process.</span></span></param>
        <param name="outboundIpAddresses"><span data-ttu-id="1b4cd-140">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-140">List of IP addresses that the app uses for outbound connections (e.g. database access).</span></span> <span data-ttu-id="1b4cd-141">Vip を含むテナントからは、現在の設定でそのサイトがホストされることができます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-141">Includes VIPs from tenants that site can be hosted with current settings.</span></span>
            <span data-ttu-id="1b4cd-142">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-142">Read-only.</span></span></param>
        <param name="possibleOutboundIpAddresses"><span data-ttu-id="1b4cd-143">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-143">List of IP addresses that the app uses for outbound connections (e.g. database access).</span></span>
            <span data-ttu-id="1b4cd-144">すべてのテナントからは、Vip が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-144">Includes VIPs from all tenants.</span></span> <span data-ttu-id="1b4cd-145">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-145">Read-only.</span></span></param>
        <param name="containerSize"><span data-ttu-id="1b4cd-146">関数のコンテナーのサイズです。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-146">Size of the function container.</span></span></param>
        <param name="dailyMemoryTimeQuota"><span data-ttu-id="1b4cd-147">最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-147">Maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span></param>
        <param name="suspendedTill"><span data-ttu-id="1b4cd-148">アプリがメモリにクォータを超えた場合に、まで中断します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-148">App suspended till in case memory-time quota is exceeded.</span></span></param>
        <param name="maxNumberOfWorkers"><span data-ttu-id="1b4cd-149">ワーカーの最大数。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-149">Maximum number of workers.</span></span>
            <span data-ttu-id="1b4cd-150">これは、関数のコンテナーにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-150">This only applies to Functions container.</span></span></param>
        <param name="cloningInfo"><span data-ttu-id="1b4cd-151">アプリの作成時に指定した場合、ソース アプリケーションから、アプリが複製されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-151">If specified during app creation, the app is cloned from a source app.</span></span></param>
        <param name="snapshotInfo"><span data-ttu-id="1b4cd-152">アプリの作成時に指定すると、前のスナップショットから、アプリが作成されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-152">If specified during app creation, the app is created from a previous snapshot.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="1b4cd-153">アプリが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-153">Name of the resource group the app belongs to.</span></span> <span data-ttu-id="1b4cd-154">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-154">Read-only.</span></span></param>
        <param name="isDefaultContainer"><span data-ttu-id="1b4cd-155">&lt;コード&gt;true&lt;/code&gt;場合は、アプリが既定のコンテナーです。 それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-155">&lt;code&gt;true&lt;/code&gt; if the app is a default container; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="defaultHostName"><span data-ttu-id="1b4cd-156">アプリの既定のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-156">Default hostname of the app.</span></span>
            <span data-ttu-id="1b4cd-157">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-157">Read-only.</span></span></param>
        <param name="slotSwapStatus"><span data-ttu-id="1b4cd-158">最後の展開スロットのスワップ操作の状態です。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-158">Status of the last deployment slot swap operation.</span></span></param>
        <param name="httpsOnly"><span data-ttu-id="1b4cd-159">HttpsOnly: は、https 要求のみを受け入れるように web サイトを構成します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-159">HttpsOnly: configures a web site to accept only https requests.</span></span> <span data-ttu-id="1b4cd-160">問題が http 要求をリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-160">Issues redirect for http requests</span></span></param>
        <param name="identity">To be added.</param>
        <summary>
            <span data-ttu-id="1b4cd-161">サイトのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-161">Initializes a new instance of the Site class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-162">アプリの管理情報の可用性の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-162">Gets management information availability state for the app.</span></span>
            <span data-ttu-id="1b4cd-163">使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'</span><span class="sxs-lookup"><span data-stu-id="1b4cd-163">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientAffinityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientAffinityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-164">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; クライアントのアフィニティを有効にするには&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt; セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-164">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client affinity; &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="1b4cd-165">既定値は&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-165">Default is &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientCertEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-166">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; (TLS の相互認証) ですクライアント証明書認証を有効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;。lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-166">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="1b4cd-167">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-167">Default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.WebSites.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-168">取得または設定アプリの作成時に指定されている場合、ソース アプリからアプリを複製します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-168">Gets or sets if specified during app creation, the app is cloned from a source app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ContainerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-169">取得または関数のコンテナーのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-169">Gets or sets size of the function container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMemoryTimeQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DailyMemoryTimeQuota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DailyMemoryTimeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dailyMemoryTimeQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-170">取得または設定最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) を許可します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-170">Gets or sets maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-171">アプリの既定のホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-171">Gets default hostname of the app.</span></span> <span data-ttu-id="1b4cd-172">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-172">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-173">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリが有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-173">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="1b4cd-174">この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-174">Setting this value to false disables the app (takes the app offline).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabledHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-175">取得には、アプリ用のホスト名が有効になります。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-175">Gets enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span> <span data-ttu-id="1b4cd-176">それ以外の場合、アプリは、そのホスト名では処理できません。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-176">Otherwise, the app is not served on those hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-177">取得またはアプリ、アプリに使用するサービス環境を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-177">Gets or sets app Service Environment to use for the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-178">アプリに関連付けられているホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-178">Gets hostnames associated with the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HostNamesDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNamesDisabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-179">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; アプリのパブリック ホスト名を無効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp; 。gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-179">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to disable the public hostnames of the app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="1b4cd-180">場合&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリは API 管理プロセスを使用してアクセスできるのみです。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-180">If &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, the app is only accessible via API management process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-181">取得または設定 SSL ホスト名の状態は、アプリのホスト名の SSL バインドの管理に使用されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-181">Gets or sets hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HttpsOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HttpsOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HttpsOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HttpsOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HttpsOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpsOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-182">取得または設定 httpsOnly: https 要求のみを受け入れるように web サイトを構成します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-182">Gets or sets httpsOnly: configures a web site to accept only https requests.</span></span> <span data-ttu-id="1b4cd-183">問題が http 要求をリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-183">Issues redirect for http requests</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As ManagedServiceIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefaultContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-184">取得&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 場合は、アプリが既定のコンテナーです。 それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-184">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is a default container; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-185">Utc 形式で、アプリが変更された最終時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-185">Gets last time the app was modified, in UTC.</span></span> <span data-ttu-id="1b4cd-186">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-186">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-187">ワーカーの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-187">Gets maximum number of workers.</span></span>
            <span data-ttu-id="1b4cd-188">これは、関数のコンテナーにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-188">This only applies to Functions container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-189">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-189">Gets list of IP addresses that the app uses for outbound connections (e.g. database access).</span></span> <span data-ttu-id="1b4cd-190">Vip を含むテナントからは、現在の設定でそのサイトがホストされることができます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-190">Includes VIPs from tenants that site can be hosted with current settings.</span></span> <span data-ttu-id="1b4cd-191">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-191">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PossibleOutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string PossibleOutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PossibleOutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.PossibleOutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PossibleOutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.PossibleOutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.PossibleOutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.possibleOutboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-192">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-192">Gets list of IP addresses that the app uses for outbound connections (e.g. database access).</span></span> <span data-ttu-id="1b4cd-193">すべてのテナントからは、Vip が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-193">Includes VIPs from all tenants.</span></span>
            <span data-ttu-id="1b4cd-194">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-194">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repositorySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-195">リポジトリ サイトの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-195">Gets name of the repository site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reserved")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-196">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 予約されている場合は、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-196">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if reserved; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-197">アプリが属するリソース グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-197">Gets name of the resource group the app belongs to.</span></span> <span data-ttu-id="1b4cd-198">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-198">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ScmSiteAlsoStopped { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmSiteAlsoStopped")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-199">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; を、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-199">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="1b4cd-200">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-200">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-201">取得または設定として書式設定、関連付けられている、App Service プランのリソース ID:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-201">Gets or sets resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.WebSites.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-202">取得またはアプリの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-202">Gets or sets configuration of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotSwapStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-203">最後の展開スロットのスワップ操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-203">Gets status of the last deployment slot swap operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SnapshotInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotInfo As SnapshotRecoveryRequest" />
      <MemberSignature Language="F#" Value="member this.SnapshotInfo : Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SnapshotInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-204">取得または設定アプリの作成時に指定されている場合、前のスナップショットから、アプリが作成されます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-204">Gets or sets if specified during app creation, the app is created from a previous snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-205">アプリの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-205">Gets current state of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendedTill">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SuspendedTill { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SuspendedTill" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspendedTill")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-206">メモリにクォータを超えた場合に、まで中断されているアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-206">Gets app suspended till in case memory-time quota is exceeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetSwapSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-207">取得では、このアプリにスワップは展開スロットを指定します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-207">Gets specifies which deployment slot this app will swap into.</span></span>
            <span data-ttu-id="1b4cd-208">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-208">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficManagerHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-209">アプリに関連付けられている azure の Traffic Manager のホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-209">Gets azure Traffic Manager hostnames associated with the app.</span></span>
            <span data-ttu-id="1b4cd-210">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-210">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-211">取得の状態は、アプリがそのクォータ使用率を超えたかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-211">Gets state indicating whether the app has exceeded its quota usage.</span></span>
            <span data-ttu-id="1b4cd-212">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-212">Read-only.</span></span> <span data-ttu-id="1b4cd-213">使用可能な値が含まれます: 'Normal'、'を超えました'</span><span class="sxs-lookup"><span data-stu-id="1b4cd-213">Possible values include: 'Normal', 'Exceeded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="site.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b4cd-214">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-214">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1b4cd-215">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1b4cd-215">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>