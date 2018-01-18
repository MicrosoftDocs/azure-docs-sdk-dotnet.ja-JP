<Type Name="SiteConfigResource" FullName="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource">
  <TypeSignature Language="C#" Value="public class SiteConfigResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteConfigResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteConfigResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteConfigResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7c950-101">ARM リソース web アプリの構成。</span><span class="sxs-lookup"><span data-stu-id="7c950-101">Web app configuration ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c950-102">SiteConfigResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7c950-102">Initializes a new instance of the SiteConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigResource (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; numberOfWorkers = null, System.Collections.Generic.IList&lt;string&gt; defaultDocuments = null, string netFrameworkVersion = null, string phpVersion = null, string pythonVersion = null, string nodeVersion = null, string linuxFxVersion = null, Nullable&lt;bool&gt; requestTracingEnabled = null, Nullable&lt;DateTime&gt; requestTracingExpirationTime = null, Nullable&lt;bool&gt; remoteDebuggingEnabled = null, string remoteDebuggingVersion = null, Nullable&lt;bool&gt; httpLoggingEnabled = null, Nullable&lt;int&gt; logsDirectorySizeLimit = null, Nullable&lt;bool&gt; detailedErrorLoggingEnabled = null, string publishingUsername = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; appSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; connectionStrings = null, Microsoft.Azure.Management.WebSites.Models.SiteMachineKey machineKey = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; handlerMappings = null, string documentRoot = null, string scmType = null, Nullable&lt;bool&gt; use32BitWorkerProcess = null, Nullable&lt;bool&gt; webSocketsEnabled = null, Nullable&lt;bool&gt; alwaysOn = null, string javaVersion = null, string javaContainer = null, string javaContainerVersion = null, string appCommandLine = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; managedPipelineMode = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; virtualApplications = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; loadBalancing = null, Microsoft.Azure.Management.WebSites.Models.Experiments experiments = null, Microsoft.Azure.Management.WebSites.Models.SiteLimits limits = null, Nullable&lt;bool&gt; autoHealEnabled = null, Microsoft.Azure.Management.WebSites.Models.AutoHealRules autoHealRules = null, string tracingOptions = null, string vnetName = null, Microsoft.Azure.Management.WebSites.Models.CorsSettings cors = null, Microsoft.Azure.Management.WebSites.Models.PushSettings push = null, Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo apiDefinition = null, string autoSwapSlotName = null, Nullable&lt;bool&gt; localMySqlEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; ipSecurityRestrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; numberOfWorkers, class System.Collections.Generic.IList`1&lt;string&gt; defaultDocuments, string netFrameworkVersion, string phpVersion, string pythonVersion, string nodeVersion, string linuxFxVersion, valuetype System.Nullable`1&lt;bool&gt; requestTracingEnabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; requestTracingExpirationTime, valuetype System.Nullable`1&lt;bool&gt; remoteDebuggingEnabled, string remoteDebuggingVersion, valuetype System.Nullable`1&lt;bool&gt; httpLoggingEnabled, valuetype System.Nullable`1&lt;int32&gt; logsDirectorySizeLimit, valuetype System.Nullable`1&lt;bool&gt; detailedErrorLoggingEnabled, string publishingUsername, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; appSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; connectionStrings, class Microsoft.Azure.Management.WebSites.Models.SiteMachineKey machineKey, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; handlerMappings, string documentRoot, string scmType, valuetype System.Nullable`1&lt;bool&gt; use32BitWorkerProcess, valuetype System.Nullable`1&lt;bool&gt; webSocketsEnabled, valuetype System.Nullable`1&lt;bool&gt; alwaysOn, string javaVersion, string javaContainer, string javaContainerVersion, string appCommandLine, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; managedPipelineMode, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; virtualApplications, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; loadBalancing, class Microsoft.Azure.Management.WebSites.Models.Experiments experiments, class Microsoft.Azure.Management.WebSites.Models.SiteLimits limits, valuetype System.Nullable`1&lt;bool&gt; autoHealEnabled, class Microsoft.Azure.Management.WebSites.Models.AutoHealRules autoHealRules, string tracingOptions, string vnetName, class Microsoft.Azure.Management.WebSites.Models.CorsSettings cors, class Microsoft.Azure.Management.WebSites.Models.PushSettings push, class Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo apiDefinition, string autoSwapSlotName, valuetype System.Nullable`1&lt;bool&gt; localMySqlEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; ipSecurityRestrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NameValuePair},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ConnStringInfo},Microsoft.Azure.Management.WebSites.Models.SiteMachineKey,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HandlerMapping},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VirtualApplication},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing},Microsoft.Azure.Management.WebSites.Models.Experiments,Microsoft.Azure.Management.WebSites.Models.SiteLimits,System.Nullable{System.Boolean},Microsoft.Azure.Management.WebSites.Models.AutoHealRules,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.CorsSettings,Microsoft.Azure.Management.WebSites.Models.PushSettings,Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteConfigResource : string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; * Microsoft.Azure.Management.WebSites.Models.SiteMachineKey * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; * Microsoft.Azure.Management.WebSites.Models.Experiments * Microsoft.Azure.Management.WebSites.Models.SiteLimits * Nullable&lt;bool&gt; * Microsoft.Azure.Management.WebSites.Models.AutoHealRules * string * string * Microsoft.Azure.Management.WebSites.Models.CorsSettings * Microsoft.Azure.Management.WebSites.Models.PushSettings * Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo * string * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteConfigResource" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteConfigResource (id, name, kind, type, numberOfWorkers, defaultDocuments, netFrameworkVersion, phpVersion, pythonVersion, nodeVersion, linuxFxVersion, requestTracingEnabled, requestTracingExpirationTime, remoteDebuggingEnabled, remoteDebuggingVersion, httpLoggingEnabled, logsDirectorySizeLimit, detailedErrorLoggingEnabled, publishingUsername, appSettings, connectionStrings, machineKey, handlerMappings, documentRoot, scmType, use32BitWorkerProcess, webSocketsEnabled, alwaysOn, javaVersion, javaContainer, javaContainerVersion, appCommandLine, managedPipelineMode, virtualApplications, loadBalancing, experiments, limits, autoHealEnabled, autoHealRules, tracingOptions, vnetName, cors, push, apiDefinition, autoSwapSlotName, localMySqlEnabled, ipSecurityRestrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="numberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultDocuments" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="netFrameworkVersion" Type="System.String" />
        <Parameter Name="phpVersion" Type="System.String" />
        <Parameter Name="pythonVersion" Type="System.String" />
        <Parameter Name="nodeVersion" Type="System.String" />
        <Parameter Name="linuxFxVersion" Type="System.String" />
        <Parameter Name="requestTracingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requestTracingExpirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="remoteDebuggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="remoteDebuggingVersion" Type="System.String" />
        <Parameter Name="httpLoggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="logsDirectorySizeLimit" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="detailedErrorLoggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publishingUsername" Type="System.String" />
        <Parameter Name="appSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;" />
        <Parameter Name="connectionStrings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt;" />
        <Parameter Name="machineKey" Type="Microsoft.Azure.Management.WebSites.Models.SiteMachineKey" />
        <Parameter Name="handlerMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt;" />
        <Parameter Name="documentRoot" Type="System.String" />
        <Parameter Name="scmType" Type="System.String" />
        <Parameter Name="use32BitWorkerProcess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="webSocketsEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="alwaysOn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="javaVersion" Type="System.String" />
        <Parameter Name="javaContainer" Type="System.String" />
        <Parameter Name="javaContainerVersion" Type="System.String" />
        <Parameter Name="appCommandLine" Type="System.String" />
        <Parameter Name="managedPipelineMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt;" />
        <Parameter Name="virtualApplications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt;" />
        <Parameter Name="loadBalancing" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt;" />
        <Parameter Name="experiments" Type="Microsoft.Azure.Management.WebSites.Models.Experiments" />
        <Parameter Name="limits" Type="Microsoft.Azure.Management.WebSites.Models.SiteLimits" />
        <Parameter Name="autoHealEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoHealRules" Type="Microsoft.Azure.Management.WebSites.Models.AutoHealRules" />
        <Parameter Name="tracingOptions" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cors" Type="Microsoft.Azure.Management.WebSites.Models.CorsSettings" />
        <Parameter Name="push" Type="Microsoft.Azure.Management.WebSites.Models.PushSettings" />
        <Parameter Name="apiDefinition" Type="Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo" />
        <Parameter Name="autoSwapSlotName" Type="System.String" />
        <Parameter Name="localMySqlEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ipSecurityRestrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="7c950-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c950-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="7c950-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c950-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="7c950-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c950-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="7c950-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c950-106">Resource type.</span></span></param>
        <param name="numberOfWorkers"><span data-ttu-id="7c950-107">ワーカーの数。</span><span class="sxs-lookup"><span data-stu-id="7c950-107">Number of workers.</span></span></param>
        <param name="defaultDocuments"><span data-ttu-id="7c950-108">既定のドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="7c950-108">Default documents.</span></span></param>
        <param name="netFrameworkVersion"><span data-ttu-id="7c950-109">.NET framework のバージョン。</span><span class="sxs-lookup"><span data-stu-id="7c950-109">.NET Framework version.</span></span></param>
        <param name="phpVersion"><span data-ttu-id="7c950-110">PHP のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="7c950-110">Version of PHP.</span></span></param>
        <param name="pythonVersion"><span data-ttu-id="7c950-111">Python のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="7c950-111">Version of Python.</span></span></param>
        <param name="nodeVersion"><span data-ttu-id="7c950-112">Node.js のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="7c950-112">Version of Node.js.</span></span></param>
        <param name="linuxFxVersion"><span data-ttu-id="7c950-113">Linux アプリケーションのフレームワークとバージョン</span><span class="sxs-lookup"><span data-stu-id="7c950-113">Linux App Framework and version</span></span></param>
        <param name="requestTracingEnabled"><span data-ttu-id="7c950-114">&lt;コード&gt;true&lt;/code&gt;要求のトレースが有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-114">&lt;code&gt;true&lt;/code&gt; if request tracing is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="requestTracingExpirationTime"><span data-ttu-id="7c950-115">トレースの有効期限を要求します。</span><span class="sxs-lookup"><span data-stu-id="7c950-115">Request tracing expiration time.</span></span></param>
        <param name="remoteDebuggingEnabled"><span data-ttu-id="7c950-116">&lt;コード&gt;true&lt;/code&gt;場合は有効である、それ以外の場合は、リモート デバッグ&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-116">&lt;code&gt;true&lt;/code&gt; if remote debugging is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="remoteDebuggingVersion"><span data-ttu-id="7c950-117">リモート デバッグ バージョンです。</span><span class="sxs-lookup"><span data-stu-id="7c950-117">Remote debugging version.</span></span></param>
        <param name="httpLoggingEnabled"><span data-ttu-id="7c950-118">&lt;コード&gt;true&lt;/code&gt; HTTP ログ記録が有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-118">&lt;code&gt;true&lt;/code&gt; if HTTP logging is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="logsDirectorySizeLimit"><span data-ttu-id="7c950-119">HTTP では、ディレクトリ サイズの上限を記録します。</span><span class="sxs-lookup"><span data-stu-id="7c950-119">HTTP logs directory size limit.</span></span></param>
        <param name="detailedErrorLoggingEnabled"><span data-ttu-id="7c950-120">&lt;コード&gt;true&lt;/code&gt;詳細なエラーのログ記録が有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-120">&lt;code&gt;true&lt;/code&gt; if detailed error logging is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="publishingUsername"><span data-ttu-id="7c950-121">発行ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="7c950-121">Publishing user name.</span></span></param>
        <param name="appSettings"><span data-ttu-id="7c950-122">アプリケーション設定。</span><span class="sxs-lookup"><span data-stu-id="7c950-122">Application settings.</span></span></param>
        <param name="connectionStrings"><span data-ttu-id="7c950-123">接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="7c950-123">Connection strings.</span></span></param>
        <param name="machineKey"><span data-ttu-id="7c950-124">サイト MachineKey です。</span><span class="sxs-lookup"><span data-stu-id="7c950-124">Site MachineKey.</span></span></param>
        <param name="handlerMappings"><span data-ttu-id="7c950-125">ハンドラー マッピングします。</span><span class="sxs-lookup"><span data-stu-id="7c950-125">Handler mappings.</span></span></param>
        <param name="documentRoot"><span data-ttu-id="7c950-126">ドキュメントのルートです。</span><span class="sxs-lookup"><span data-stu-id="7c950-126">Document root.</span></span></param>
        <param name="scmType"><span data-ttu-id="7c950-127">SCM 型です。</span><span class="sxs-lookup"><span data-stu-id="7c950-127">SCM type.</span></span> <span data-ttu-id="7c950-128">使用可能な値が含まれます 'None'、'Dropbox'、'Tfs'、'LocalGit'、'GitHub'、'CodePlexGit'、'CodePlexHg'、'BitbucketGit'、'BitbucketHg'、'ExternalGit'、'ExternalHg'、'OneDrive'、'VSO'。</span><span class="sxs-lookup"><span data-stu-id="7c950-128">Possible values include: 'None', 'Dropbox', 'Tfs', 'LocalGit', 'GitHub', 'CodePlexGit', 'CodePlexHg', 'BitbucketGit', 'BitbucketHg', 'ExternalGit', 'ExternalHg', 'OneDrive', 'VSO'</span></span></param>
        <param name="use32BitWorkerProcess"><span data-ttu-id="7c950-129">&lt;コード&gt;true&lt;/code&gt; ; 32 ビット ワーカー プロセスを使用してそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-129">&lt;code&gt;true&lt;/code&gt; to use 32-bit worker process; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="webSocketsEnabled"><span data-ttu-id="7c950-130">&lt;コード&gt;true&lt;/code&gt; WebSocket が有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-130">&lt;code&gt;true&lt;/code&gt; if WebSocket is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="alwaysOn"><span data-ttu-id="7c950-131">&lt;コード&gt;true&lt;/code&gt; Always On が有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-131">&lt;code&gt;true&lt;/code&gt; if Always On is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="javaVersion"><span data-ttu-id="7c950-132">Java バージョンです。</span><span class="sxs-lookup"><span data-stu-id="7c950-132">Java version.</span></span></param>
        <param name="javaContainer"><span data-ttu-id="7c950-133">Java コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="7c950-133">Java container.</span></span></param>
        <param name="javaContainerVersion"><span data-ttu-id="7c950-134">コンテナーの Java バージョン。</span><span class="sxs-lookup"><span data-stu-id="7c950-134">Java container version.</span></span></param>
        <param name="appCommandLine"><span data-ttu-id="7c950-135">アプリのコマンド ラインを起動します。</span><span class="sxs-lookup"><span data-stu-id="7c950-135">App command line to launch.</span></span></param>
        <param name="managedPipelineMode"><span data-ttu-id="7c950-136">マネージ パイプライン モードです。</span><span class="sxs-lookup"><span data-stu-id="7c950-136">Managed pipeline mode.</span></span> <span data-ttu-id="7c950-137">使用可能な値が含まれます: '統合'、'Classic'</span><span class="sxs-lookup"><span data-stu-id="7c950-137">Possible values include: 'Integrated', 'Classic'</span></span></param>
        <param name="virtualApplications"><span data-ttu-id="7c950-138">仮想アプリケーション。</span><span class="sxs-lookup"><span data-stu-id="7c950-138">Virtual applications.</span></span></param>
        <param name="loadBalancing"><span data-ttu-id="7c950-139">サイトの負荷を分散します。</span><span class="sxs-lookup"><span data-stu-id="7c950-139">Site load balancing.</span></span> <span data-ttu-id="7c950-140">使用可能な値が含まれます: 'WeightedRoundRobin'、'LeastRequests'、'LeastResponseTime'、'WeightedTotalTraffic'、'RequestHash'</span><span class="sxs-lookup"><span data-stu-id="7c950-140">Possible values include: 'WeightedRoundRobin', 'LeastRequests', 'LeastResponseTime', 'WeightedTotalTraffic', 'RequestHash'</span></span></param>
        <param name="experiments"><span data-ttu-id="7c950-141">これは、polymophic 型の回避です。</span><span class="sxs-lookup"><span data-stu-id="7c950-141">This is work around for polymophic types.</span></span></param>
        <param name="limits"><span data-ttu-id="7c950-142">サイトの制限。</span><span class="sxs-lookup"><span data-stu-id="7c950-142">Site limits.</span></span></param>
        <param name="autoHealEnabled"><span data-ttu-id="7c950-143">&lt;コード&gt;true&lt;/code&gt;場合は自動修復が有効である、それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-143">&lt;code&gt;true&lt;/code&gt; if Auto Heal is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="autoHealRules"><span data-ttu-id="7c950-144">自動 Heal ルール。</span><span class="sxs-lookup"><span data-stu-id="7c950-144">Auto Heal rules.</span></span></param>
        <param name="tracingOptions"><span data-ttu-id="7c950-145">トレース オプション。</span><span class="sxs-lookup"><span data-stu-id="7c950-145">Tracing options.</span></span></param>
        <param name="vnetName"><span data-ttu-id="7c950-146">仮想ネットワーク名です。</span><span class="sxs-lookup"><span data-stu-id="7c950-146">Virtual Network name.</span></span></param>
        <param name="cors"><span data-ttu-id="7c950-147">クロス オリジン リソース共有 (CORS) の設定です。</span><span class="sxs-lookup"><span data-stu-id="7c950-147">Cross-Origin Resource Sharing (CORS) settings.</span></span></param>
        <param name="push"><span data-ttu-id="7c950-148">エンドポイントの設定をプッシュします。</span><span class="sxs-lookup"><span data-stu-id="7c950-148">Push endpoint settings.</span></span></param>
        <param name="apiDefinition"><span data-ttu-id="7c950-149">アプリの正式な API 定義に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="7c950-149">Information about the formal API definition for the app.</span></span></param>
        <param name="autoSwapSlotName"><span data-ttu-id="7c950-150">自動スワップ スロットの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c950-150">Auto-swap slot name.</span></span></param>
        <param name="localMySqlEnabled"><span data-ttu-id="7c950-151">&lt;コード&gt;true&lt;/code&gt;ローカル MySQL; を有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="7c950-151">&lt;code&gt;true&lt;/code&gt; to enable local MySQL; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="ipSecurityRestrictions"><span data-ttu-id="7c950-152">IP セキュリティ制限します。</span><span class="sxs-lookup"><span data-stu-id="7c950-152">IP security restrictions.</span></span></param>
        <summary>
            <span data-ttu-id="7c950-153">SiteConfigResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7c950-153">Initializes a new instance of the SiteConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlwaysOn">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AlwaysOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AlwaysOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AlwaysOn" />
      <MemberSignature Language="VB.NET" Value="Public Property AlwaysOn As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AlwaysOn : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AlwaysOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alwaysOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-154">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; Always On が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-154">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Always On is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiDefinition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo ApiDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo ApiDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ApiDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiDefinition As ApiDefinitionInfo" />
      <MemberSignature Language="F#" Value="member this.ApiDefinition : Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ApiDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiDefinition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ApiDefinitionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-155">取得またはアプリの正式な API 定義に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-155">Gets or sets information about the formal API definition for the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppCommandLine">
      <MemberSignature Language="C#" Value="public string AppCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AppCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property AppCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.AppCommandLine : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AppCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-156">取得またはアプリを起動するコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-156">Gets or sets app command line to launch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; AppSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; AppSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AppSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.AppSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AppSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-157">取得またはアプリケーションの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-157">Gets or sets application settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoHealEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoHealEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoHealEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoHealEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoHealEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoHealEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoHealEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoHealEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-158">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 場合は自動修復が有効である、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-158">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Auto Heal is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoHealRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.AutoHealRules AutoHealRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.AutoHealRules AutoHealRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoHealRules" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoHealRules As AutoHealRules" />
      <MemberSignature Language="F#" Value="member this.AutoHealRules : Microsoft.Azure.Management.WebSites.Models.AutoHealRules with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoHealRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoHealRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AutoHealRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-159">取得または自動 Heal ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-159">Gets or sets auto Heal rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoSwapSlotName">
      <MemberSignature Language="C#" Value="public string AutoSwapSlotName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoSwapSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoSwapSlotName" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoSwapSlotName As String" />
      <MemberSignature Language="F#" Value="member this.AutoSwapSlotName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.AutoSwapSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoSwapSlotName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-160">取得または自動スワップ スロット名を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-160">Gets or sets auto-swap slot name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStrings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; ConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; ConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionStrings As IList(Of ConnStringInfo)" />
      <MemberSignature Language="F#" Value="member this.ConnectionStrings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ConnStringInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-161">取得または接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-161">Gets or sets connection strings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CorsSettings Cors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CorsSettings Cors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Cors" />
      <MemberSignature Language="VB.NET" Value="Public Property Cors As CorsSettings" />
      <MemberSignature Language="F#" Value="member this.Cors : Microsoft.Azure.Management.WebSites.Models.CorsSettings with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Cors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CorsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-162">取得またはクロス オリジン リソース共有 (CORS) の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-162">Gets or sets cross-Origin Resource Sharing (CORS) settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDocuments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DefaultDocuments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DefaultDocuments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DefaultDocuments" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDocuments As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DefaultDocuments : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DefaultDocuments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultDocuments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-163">取得または既定のドキュメントを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-163">Gets or sets default documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedErrorLoggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DetailedErrorLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DetailedErrorLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DetailedErrorLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedErrorLoggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DetailedErrorLoggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DetailedErrorLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedErrorLoggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-164">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 詳細なエラーのログ記録が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-164">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if detailed error logging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentRoot">
      <MemberSignature Language="C#" Value="public string DocumentRoot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentRoot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DocumentRoot" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentRoot As String" />
      <MemberSignature Language="F#" Value="member this.DocumentRoot : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.DocumentRoot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.documentRoot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-165">取得またはドキュメントのルートを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-165">Gets or sets document root.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Experiments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Experiments Experiments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Experiments Experiments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Experiments" />
      <MemberSignature Language="VB.NET" Value="Public Property Experiments As Experiments" />
      <MemberSignature Language="F#" Value="member this.Experiments : Microsoft.Azure.Management.WebSites.Models.Experiments with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Experiments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.experiments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Experiments</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-166">取得または設定 polymophic 型の回避です。</span><span class="sxs-lookup"><span data-stu-id="7c950-166">Gets or sets this is work around for polymophic types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandlerMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; HandlerMappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; HandlerMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.HandlerMappings" />
      <MemberSignature Language="VB.NET" Value="Public Property HandlerMappings As IList(Of HandlerMapping)" />
      <MemberSignature Language="F#" Value="member this.HandlerMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.HandlerMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.handlerMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HandlerMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-167">取得またはハンドラー マッピングを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-167">Gets or sets handler mappings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpLoggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HttpLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HttpLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.HttpLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpLoggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HttpLoggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.HttpLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpLoggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-168">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; HTTP ログ記録が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-168">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if HTTP logging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpSecurityRestrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; IpSecurityRestrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; IpSecurityRestrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.IpSecurityRestrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property IpSecurityRestrictions As IList(Of IpSecurityRestriction)" />
      <MemberSignature Language="F#" Value="member this.IpSecurityRestrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.IpSecurityRestrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipSecurityRestrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-169">取得または IP セキュリティ制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-169">Gets or sets IP security restrictions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainer">
      <MemberSignature Language="C#" Value="public string JavaContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaContainer As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainer : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-170">取得または java コンテナーを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-170">Gets or sets java container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainerVersion">
      <MemberSignature Language="C#" Value="public string JavaContainerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaContainerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaContainerVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainerVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaContainerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaContainerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-171">取得またはコンテナーの java バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-171">Gets or sets java container version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaVersion">
      <MemberSignature Language="C#" Value="public string JavaVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.JavaVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-172">取得または java バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-172">Gets or sets java version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SiteLimits Limits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SiteLimits Limits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Limits" />
      <MemberSignature Language="VB.NET" Value="Public Property Limits As SiteLimits" />
      <MemberSignature Language="F#" Value="member this.Limits : Microsoft.Azure.Management.WebSites.Models.SiteLimits with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Limits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.limits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteLimits</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-173">取得またはサイトの制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-173">Gets or sets site limits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxFxVersion">
      <MemberSignature Language="C#" Value="public string LinuxFxVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinuxFxVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LinuxFxVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxFxVersion As String" />
      <MemberSignature Language="F#" Value="member this.LinuxFxVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LinuxFxVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linuxFxVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-174">取得または設定の linux アプリケーション フレームワークとバージョン</span><span class="sxs-lookup"><span data-stu-id="7c950-174">Gets or sets linux App Framework and version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancing">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; LoadBalancing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; LoadBalancing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LoadBalancing" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancing As Nullable(Of SiteLoadBalancing)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancing : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LoadBalancing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteLoadBalancing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-175">取得またはサイトの負荷分散を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-175">Gets or sets site load balancing.</span></span> <span data-ttu-id="7c950-176">使用可能な値が含まれます: 'WeightedRoundRobin'、'LeastRequests'、'LeastResponseTime'、'WeightedTotalTraffic'、'RequestHash'</span><span class="sxs-lookup"><span data-stu-id="7c950-176">Possible values include: 'WeightedRoundRobin', 'LeastRequests', 'LeastResponseTime', 'WeightedTotalTraffic', 'RequestHash'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMySqlEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LocalMySqlEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LocalMySqlEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LocalMySqlEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalMySqlEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LocalMySqlEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LocalMySqlEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localMySqlEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-177">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; ローカル MySQL; を有効にするそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-177">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable local MySQL; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogsDirectorySizeLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LogsDirectorySizeLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LogsDirectorySizeLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LogsDirectorySizeLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property LogsDirectorySizeLimit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LogsDirectorySizeLimit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.LogsDirectorySizeLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.logsDirectorySizeLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-178">取得または HTTP ログ ディレクトリのサイズ制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-178">Gets or sets HTTP logs directory size limit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MachineKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SiteMachineKey MachineKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SiteMachineKey MachineKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.MachineKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MachineKey As SiteMachineKey" />
      <MemberSignature Language="F#" Value="member this.MachineKey : Microsoft.Azure.Management.WebSites.Models.SiteMachineKey" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.MachineKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.machineKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteMachineKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-179">サイトの MachineKey を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c950-179">Gets site MachineKey.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; ManagedPipelineMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; ManagedPipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ManagedPipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedPipelineMode As Nullable(Of ManagedPipelineMode)" />
      <MemberSignature Language="F#" Value="member this.ManagedPipelineMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ManagedPipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managedPipelineMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ManagedPipelineMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-180">取得またはマネージ パイプライン モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-180">Gets or sets managed pipeline mode.</span></span> <span data-ttu-id="7c950-181">使用可能な値が含まれます: '統合'、'Classic'</span><span class="sxs-lookup"><span data-stu-id="7c950-181">Possible values include: 'Integrated', 'Classic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetFrameworkVersion">
      <MemberSignature Language="C#" Value="public string NetFrameworkVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetFrameworkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NetFrameworkVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property NetFrameworkVersion As String" />
      <MemberSignature Language="F#" Value="member this.NetFrameworkVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NetFrameworkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.netFrameworkVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-182">取得または .NET Framework のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-182">Gets or sets .NET Framework version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeVersion">
      <MemberSignature Language="C#" Value="public string NodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.NodeVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-183">取得または Node.js のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-183">Gets or sets version of Node.js.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfWorkers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfWorkers : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.NumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-184">取得またはワーカーの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-184">Gets or sets number of workers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhpVersion">
      <MemberSignature Language="C#" Value="public string PhpVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PhpVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PhpVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PhpVersion As String" />
      <MemberSignature Language="F#" Value="member this.PhpVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PhpVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.phpVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-185">取得または PHP のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-185">Gets or sets version of PHP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingUsername">
      <MemberSignature Language="C#" Value="public string PublishingUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PublishingUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingUsername As String" />
      <MemberSignature Language="F#" Value="member this.PublishingUsername : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PublishingUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-186">取得または発行ユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-186">Gets or sets publishing user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Push">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.PushSettings Push { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.PushSettings Push" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Push" />
      <MemberSignature Language="VB.NET" Value="Public Property Push As PushSettings" />
      <MemberSignature Language="F#" Value="member this.Push : Microsoft.Azure.Management.WebSites.Models.PushSettings with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Push" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.push")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.PushSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-187">取得またはプッシュ エンドポイントの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-187">Gets or sets push endpoint settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonVersion">
      <MemberSignature Language="C#" Value="public string PythonVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PythonVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonVersion As String" />
      <MemberSignature Language="F#" Value="member this.PythonVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.PythonVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pythonVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-188">取得または Python のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-188">Gets or sets version of Python.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RemoteDebuggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RemoteDebuggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RemoteDebuggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteDebuggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RemoteDebuggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteDebuggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-189">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; リモート デバッグが有効である、それ以外の場合、場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-189">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if remote debugging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingVersion">
      <MemberSignature Language="C#" Value="public string RemoteDebuggingVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteDebuggingVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RemoteDebuggingVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteDebuggingVersion As String" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RemoteDebuggingVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteDebuggingVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-190">取得またはリモートのデバッグ バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-190">Gets or sets remote debugging version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTracingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequestTracingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequestTracingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RequestTracingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTracingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequestTracingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RequestTracingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTracingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-191">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 要求のトレースが有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-191">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if request tracing is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTracingExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RequestTracingExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RequestTracingExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RequestTracingExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTracingExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RequestTracingExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.RequestTracingExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTracingExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-192">取得または要求のトレースの有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-192">Gets or sets request tracing expiration time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmType">
      <MemberSignature Language="C#" Value="public string ScmType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScmType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ScmType" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmType As String" />
      <MemberSignature Language="F#" Value="member this.ScmType : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.ScmType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-193">取得または SCM 型を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-193">Gets or sets SCM type.</span></span> <span data-ttu-id="7c950-194">使用可能な値が含まれます 'None'、'Dropbox'、'Tfs'、'LocalGit'、'GitHub'、'CodePlexGit'、'CodePlexHg'、'BitbucketGit'、'BitbucketHg'、'ExternalGit'、'ExternalHg'、'OneDrive'、'VSO'。</span><span class="sxs-lookup"><span data-stu-id="7c950-194">Possible values include: 'None', 'Dropbox', 'Tfs', 'LocalGit', 'GitHub', 'CodePlexGit', 'CodePlexHg', 'BitbucketGit', 'BitbucketHg', 'ExternalGit', 'ExternalHg', 'OneDrive', 'VSO'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TracingOptions">
      <MemberSignature Language="C#" Value="public string TracingOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TracingOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.TracingOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property TracingOptions As String" />
      <MemberSignature Language="F#" Value="member this.TracingOptions : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.TracingOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tracingOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-195">取得またはトレース オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-195">Gets or sets tracing options.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Use32BitWorkerProcess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Use32BitWorkerProcess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Use32BitWorkerProcess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Use32BitWorkerProcess" />
      <MemberSignature Language="VB.NET" Value="Public Property Use32BitWorkerProcess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Use32BitWorkerProcess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.Use32BitWorkerProcess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.use32BitWorkerProcess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-196">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 32 ビット ワーカー プロセスを使用してそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-196">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to use 32-bit worker process; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualApplications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; VirtualApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; VirtualApplications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.VirtualApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualApplications As IList(Of VirtualApplication)" />
      <MemberSignature Language="F#" Value="member this.VirtualApplications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.VirtualApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualApplications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualApplication&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-197">取得または、仮想アプリケーションを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-197">Gets or sets virtual applications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-198">取得または仮想ネットワーク名を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c950-198">Gets or sets virtual Network name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebSocketsEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WebSocketsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WebSocketsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.WebSocketsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property WebSocketsEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WebSocketsEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigResource.WebSocketsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webSocketsEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c950-199">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; WebSocket が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="7c950-199">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if WebSocket is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>