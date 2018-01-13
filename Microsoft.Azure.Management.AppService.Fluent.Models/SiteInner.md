<Type Name="SiteInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner">
  <TypeSignature Language="C#" Value="public class SiteInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SiteInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="675db-101">Web アプリ、モバイル アプリ バックエンドでは、または API アプリ。</span><span class="sxs-lookup"><span data-stu-id="675db-101">A web app, a mobile app backend, or an API app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="675db-102">SiteInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="675db-102">Initializes a new instance of the SiteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string kind = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; premiumAppDeployed = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, string microService = null, string gatewaySiteName = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string kind, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; premiumAppDeployed, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile, string microService, string gatewaySiteName, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner (location, id, name, type, tags, kind, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, premiumAppDeployed, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, microService, gatewaySiteName, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="premiumAppDeployed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile" />
        <Parameter Name="microService" Type="System.String" />
        <Parameter Name="gatewaySiteName" Type="System.String" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="kind"><span data-ttu-id="675db-103">サイトの種類</span><span class="sxs-lookup"><span data-stu-id="675db-103">The kind of the site</span></span></param>
        <param name="state"><span data-ttu-id="675db-104">アプリの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="675db-104">Current state of the app.</span></span></param>
        <param name="hostNames"><span data-ttu-id="675db-105">アプリに関連付けられているホスト名です。</span><span class="sxs-lookup"><span data-stu-id="675db-105">Hostnames associated with the app.</span></span></param>
        <param name="repositorySiteName"><span data-ttu-id="675db-106">リポジトリ サイトの名前です。</span><span class="sxs-lookup"><span data-stu-id="675db-106">Name of the repository site.</span></span></param>
        <param name="usageState"><span data-ttu-id="675db-107">アプリでのクォータ使用率が超過するかどうかを示す状態です。</span><span class="sxs-lookup"><span data-stu-id="675db-107">State indicating whether the app has exceeded its quota usage.</span></span> <span data-ttu-id="675db-108">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-108">Read-only.</span></span> <span data-ttu-id="675db-109">使用可能な値が含まれます: 'Normal'、'を超えました'</span><span class="sxs-lookup"><span data-stu-id="675db-109">Possible values include: 'Normal', 'Exceeded'</span></span></param>
        <param name="enabled"><span data-ttu-id="675db-110">&lt;コード&gt;true&lt;/code&gt; 、アプリが有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-110">&lt;code&gt;true&lt;/code&gt; if the app is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="675db-111">この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。</span><span class="sxs-lookup"><span data-stu-id="675db-111">Setting this value to false disables the app (takes the app offline).</span></span></param>
        <param name="enabledHostNames"><span data-ttu-id="675db-112">アプリの有効なホスト名です。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。</span><span class="sxs-lookup"><span data-stu-id="675db-112">Enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span>
            <span data-ttu-id="675db-113">それ以外の場合、アプリは、そのホスト名では処理できません。</span><span class="sxs-lookup"><span data-stu-id="675db-113">Otherwise, the app is not served on those hostnames.</span></span></param>
        <param name="availabilityState"><span data-ttu-id="675db-114">アプリの管理情報の可用性の状態。</span><span class="sxs-lookup"><span data-stu-id="675db-114">Management information availability state for the app.</span></span> <span data-ttu-id="675db-115">使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'</span><span class="sxs-lookup"><span data-stu-id="675db-115">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span></param>
        <param name="hostNameSslStates"><span data-ttu-id="675db-116">ホスト名の SSL の状態は、アプリのホスト名の SSL バインドの管理に使用されます。</span><span class="sxs-lookup"><span data-stu-id="675db-116">Hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="675db-117">リソース ID、関連付けられている App Service プランの設定として書式設定:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="675db-117">Resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span></param>
        <param name="reserved"><span data-ttu-id="675db-118">&lt;コード&gt;true&lt;/code&gt;予約されている場合は、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-118">&lt;code&gt;true&lt;/code&gt; if reserved; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="lastModifiedTimeUtc"><span data-ttu-id="675db-119">最後の時刻 (utc) で、アプリが変更されました。</span><span class="sxs-lookup"><span data-stu-id="675db-119">Last time the app was modified, in UTC.</span></span> <span data-ttu-id="675db-120">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-120">Read-only.</span></span></param>
        <param name="siteConfig"><span data-ttu-id="675db-121">アプリの構成。</span><span class="sxs-lookup"><span data-stu-id="675db-121">Configuration of the app.</span></span></param>
        <param name="trafficManagerHostNames"><span data-ttu-id="675db-122">Azure Traffic Manager のホスト名は、アプリに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="675db-122">Azure Traffic Manager hostnames associated with the app.</span></span> <span data-ttu-id="675db-123">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-123">Read-only.</span></span></param>
        <param name="premiumAppDeployed"><span data-ttu-id="675db-124">Premium アプリとしてアプリが展開されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="675db-124">Indicates whether app is deployed as a premium app.</span></span></param>
        <param name="scmSiteAlsoStopped"><span data-ttu-id="675db-125">&lt;コード&gt;true&lt;/code&gt; 、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-125">&lt;code&gt;true&lt;/code&gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="675db-126">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-126">The default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="targetSwapSlot"><span data-ttu-id="675db-127">このアプリにスワップは展開スロットを指定します。</span><span class="sxs-lookup"><span data-stu-id="675db-127">Specifies which deployment slot this app will swap into.</span></span> <span data-ttu-id="675db-128">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-128">Read-only.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="675db-129">アプリの使用を app Service 環境。</span><span class="sxs-lookup"><span data-stu-id="675db-129">App Service Environment to use for the app.</span></span></param>
        <param name="microService"><span data-ttu-id="675db-130">マイクロ サービスなどのアプリ、ロジック。</span><span class="sxs-lookup"><span data-stu-id="675db-130">Micro services like apps, logic apps.</span></span></param>
        <param name="gatewaySiteName"><span data-ttu-id="675db-131">アプリに関連付けられたゲートウェイ アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="675db-131">Name of gateway app associated with the app.</span></span></param>
        <param name="clientAffinityEnabled"><span data-ttu-id="675db-132">&lt;コード&gt;true&lt;/code&gt;クライアントのアフィニティを有効にするには&lt;コード&gt;false&lt;/code&gt;セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。</span><span class="sxs-lookup"><span data-stu-id="675db-132">&lt;code&gt;true&lt;/code&gt; to enable client affinity; &lt;code&gt;false&lt;/code&gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="675db-133">既定値は&lt;コード&gt;true&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-133">Default is &lt;code&gt;true&lt;/code&gt;.</span></span></param>
        <param name="clientCertEnabled"><span data-ttu-id="675db-134">&lt;コード&gt;true&lt;/code&gt; (TLS の相互認証) です。 クライアント証明書認証を有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-134">&lt;code&gt;true&lt;/code&gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="675db-135">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-135">Default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostNamesDisabled"><span data-ttu-id="675db-136">&lt;コード&gt;true&lt;/code&gt; ; アプリのパブリック ホスト名を無効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-136">&lt;code&gt;true&lt;/code&gt; to disable the public hostnames of the app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span>
            <span data-ttu-id="675db-137">場合&lt;コード&gt;true&lt;/code&gt;アプリは API 管理プロセスを使用してアクセスできるのみです。</span><span class="sxs-lookup"><span data-stu-id="675db-137">If &lt;code&gt;true&lt;/code&gt;, the app is only accessible via API management process.</span></span></param>
        <param name="outboundIpAddresses"><span data-ttu-id="675db-138">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="675db-138">List of IP addresses that the app uses for outbound connections (e.g. database access).</span></span>
            <span data-ttu-id="675db-139">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-139">Read-only.</span></span></param>
        <param name="containerSize"><span data-ttu-id="675db-140">関数のコンテナーのサイズです。</span><span class="sxs-lookup"><span data-stu-id="675db-140">Size of the function container.</span></span></param>
        <param name="dailyMemoryTimeQuota"><span data-ttu-id="675db-141">最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) です。</span><span class="sxs-lookup"><span data-stu-id="675db-141">Maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span></param>
        <param name="suspendedTill"><span data-ttu-id="675db-142">アプリがメモリにクォータを超えた場合に、まで中断します。</span><span class="sxs-lookup"><span data-stu-id="675db-142">App suspended till in case memory-time quota is exceeded.</span></span></param>
        <param name="maxNumberOfWorkers"><span data-ttu-id="675db-143">ワーカーの最大数。</span><span class="sxs-lookup"><span data-stu-id="675db-143">Maximum number of workers.</span></span>
            <span data-ttu-id="675db-144">これは、関数のコンテナーにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="675db-144">This only applies to Functions container.</span></span></param>
        <param name="cloningInfo"><span data-ttu-id="675db-145">アプリの作成時に指定した場合、ソース アプリケーションから、アプリが複製されます。</span><span class="sxs-lookup"><span data-stu-id="675db-145">If specified during app creation, the app is cloned from a source app.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="675db-146">アプリが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="675db-146">Name of the resource group the app belongs to.</span></span> <span data-ttu-id="675db-147">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-147">Read-only.</span></span></param>
        <param name="isDefaultContainer"><span data-ttu-id="675db-148">&lt;コード&gt;true&lt;/code&gt;場合は、アプリが既定のコンテナーです。 それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="675db-148">&lt;code&gt;true&lt;/code&gt; if the app is a default container; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="defaultHostName"><span data-ttu-id="675db-149">アプリの既定のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="675db-149">Default hostname of the app.</span></span>
            <span data-ttu-id="675db-150">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-150">Read-only.</span></span></param>
        <param name="slotSwapStatus"><span data-ttu-id="675db-151">最後の展開スロットのスワップ操作の状態です。</span><span class="sxs-lookup"><span data-stu-id="675db-151">Status of the last deployment slot swap operation.</span></span></param>
        <summary>
            <span data-ttu-id="675db-152">SiteInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="675db-152">Initializes a new instance of the SiteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-153">アプリの管理情報の可用性の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-153">Gets management information availability state for the app.</span></span>
            <span data-ttu-id="675db-154">使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'</span><span class="sxs-lookup"><span data-stu-id="675db-154">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientAffinityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-155">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; クライアントのアフィニティを有効にするには&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt; セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。</span><span class="sxs-lookup"><span data-stu-id="675db-155">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client affinity; &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="675db-156">既定値は&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-156">Default is &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientCertEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-157">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; (TLS の相互認証) ですクライアント証明書認証を有効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;。lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-157">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="675db-158">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-158">Default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-159">取得または設定アプリの作成時に指定されている場合、ソース アプリからアプリを複製します。</span><span class="sxs-lookup"><span data-stu-id="675db-159">Gets or sets if specified during app creation, the app is cloned from a source app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ContainerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-160">取得または関数のコンテナーのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="675db-160">Gets or sets size of the function container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMemoryTimeQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DailyMemoryTimeQuota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DailyMemoryTimeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-161">取得または設定最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) を許可します。</span><span class="sxs-lookup"><span data-stu-id="675db-161">Gets or sets maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-162">アプリの既定のホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-162">Gets default hostname of the app.</span></span> <span data-ttu-id="675db-163">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-163">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-164">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリが有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-164">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="675db-165">この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。</span><span class="sxs-lookup"><span data-stu-id="675db-165">Setting this value to false disables the app (takes the app offline).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-166">取得には、アプリ用のホスト名が有効になります。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。</span><span class="sxs-lookup"><span data-stu-id="675db-166">Gets enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span> <span data-ttu-id="675db-167">それ以外の場合、アプリは、そのホスト名では処理できません。</span><span class="sxs-lookup"><span data-stu-id="675db-167">Otherwise, the app is not served on those hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewaySiteName">
      <MemberSignature Language="C#" Value="public string GatewaySiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewaySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.GatewaySiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewaySiteName As String" />
      <MemberSignature Language="F#" Value="member this.GatewaySiteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.GatewaySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewaySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-168">取得またはアプリに関連付けられたゲートウェイ アプリの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="675db-168">Gets or sets name of gateway app associated with the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-169">取得またはアプリ、アプリに使用するサービス環境を設定します。</span><span class="sxs-lookup"><span data-stu-id="675db-169">Gets or sets app Service Environment to use for the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-170">アプリに関連付けられているホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-170">Gets hostnames associated with the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HostNamesDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-171">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; アプリのパブリック ホスト名を無効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp; 。gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-171">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to disable the public hostnames of the app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="675db-172">場合&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリは API 管理プロセスを使用してアクセスできるのみです。</span><span class="sxs-lookup"><span data-stu-id="675db-172">If &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, the app is only accessible via API management process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-173">取得または設定 SSL ホスト名の状態は、アプリのホスト名の SSL バインドの管理に使用されます。</span><span class="sxs-lookup"><span data-stu-id="675db-173">Gets or sets hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-174">取得&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 場合は、アプリが既定のコンテナーです。 それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-174">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is a default container; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-175">アプリの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-175">Gets the kind of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-176">Utc 形式で、アプリが変更された最終時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-176">Gets last time the app was modified, in UTC.</span></span> <span data-ttu-id="675db-177">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-177">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-178">ワーカーの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-178">Gets maximum number of workers.</span></span>
            <span data-ttu-id="675db-179">これは、関数のコンテナーにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="675db-179">This only applies to Functions container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicroService">
      <MemberSignature Language="C#" Value="public string MicroService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicroService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.MicroService" />
      <MemberSignature Language="VB.NET" Value="Public Property MicroService As String" />
      <MemberSignature Language="F#" Value="member this.MicroService : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.MicroService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-180">取得またはアプリ、ロジックのアプリと同様にマイクロ サービスを設定します。</span><span class="sxs-lookup"><span data-stu-id="675db-180">Gets or sets micro services like apps, logic apps.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-181">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-181">Gets list of IP addresses that the app uses for outbound connections (e.g. database access).</span></span> <span data-ttu-id="675db-182">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-182">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumAppDeployed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PremiumAppDeployed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PremiumAppDeployed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.PremiumAppDeployed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumAppDeployed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PremiumAppDeployed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.PremiumAppDeployed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.premiumAppDeployed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-183">取得では、premium アプリとしてアプリが展開されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="675db-183">Gets indicates whether app is deployed as a premium app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-184">リポジトリ サイトの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-184">Gets name of the repository site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-185">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 予約されている場合は、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-185">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if reserved; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-186">アプリが属するリソース グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-186">Gets name of the resource group the app belongs to.</span></span> <span data-ttu-id="675db-187">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-187">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ScmSiteAlsoStopped { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-188">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; を、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-188">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="675db-189">既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="675db-189">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-190">取得または設定として書式設定、関連付けられている、App Service プランのリソース ID:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="675db-190">Gets or sets resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-191">取得またはアプリの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="675db-191">Gets or sets configuration of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotSwapStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-192">最後の展開スロットのスワップ操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-192">Gets status of the last deployment slot swap operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-193">アプリの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-193">Gets current state of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendedTill">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SuspendedTill { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SuspendedTill" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-194">メモリにクォータを超えた場合に、まで中断されているアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-194">Gets app suspended till in case memory-time quota is exceeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-195">取得では、このアプリにスワップは展開スロットを指定します。</span><span class="sxs-lookup"><span data-stu-id="675db-195">Gets specifies which deployment slot this app will swap into.</span></span>
            <span data-ttu-id="675db-196">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-196">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="675db-197">アプリに関連付けられている azure の Traffic Manager のホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="675db-197">Gets azure Traffic Manager hostnames associated with the app.</span></span>
            <span data-ttu-id="675db-198">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-198">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="675db-199">取得の状態は、アプリがそのクォータ使用率を超えたかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="675db-199">Gets state indicating whether the app has exceeded its quota usage.</span></span>
            <span data-ttu-id="675db-200">読み取り専用。</span><span class="sxs-lookup"><span data-stu-id="675db-200">Read-only.</span></span> <span data-ttu-id="675db-201">使用可能な値が含まれます: 'Normal'、'を超えました'</span><span class="sxs-lookup"><span data-stu-id="675db-201">Possible values include: 'Normal', 'Exceeded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="siteInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="675db-202">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="675db-202">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="675db-203">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="675db-203">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>