<Type Name="AppServiceEnvironmentPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource">
  <TypeSignature Language="C#" Value="public class AppServiceEnvironmentPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceEnvironmentPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceEnvironmentPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentPatchResource = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="66413-101">App service 環境の ARM リソースです。</span><span class="sxs-lookup"><span data-stu-id="66413-101">ARM resource for a app service enviroment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66413-102">AppServiceEnvironmentPatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66413-102">Initializes a new instance of the AppServiceEnvironmentPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentPatchResource (string appServiceEnvironmentPatchResourceName, string location, Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, string id = null, string name = null, string kind = null, string type = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status = null, string vnetName = null, string vnetResourceGroupName = null, string vnetSubnetName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode = null, string multiSize = null, Nullable&lt;int&gt; multiRoleCount = null, Nullable&lt;int&gt; ipsslAddressCount = null, string databaseEdition = null, string databaseServiceObjective = null, Nullable&lt;int&gt; upgradeDomains = null, string subscriptionId = null, string dnsSuffix = null, string lastAction = null, string lastActionResult = null, string allowedMultiSizes = null, string allowedWorkerSizes = null, Nullable&lt;int&gt; maximumNumberOfMachines = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList = null, Nullable&lt;bool&gt; environmentIsHealthy = null, string environmentStatus = null, string resourceGroup = null, Nullable&lt;int&gt; frontEndScaleFactor = null, Nullable&lt;int&gt; defaultFrontEndScaleFactor = null, string apiManagementAccountId = null, Nullable&lt;bool&gt; suspended = null, Nullable&lt;bool&gt; dynamicCacheEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings = null, System.Collections.Generic.IList&lt;string&gt; userWhitelistedIpRanges = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string appServiceEnvironmentPatchResourceName, string location, class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, string id, string name, string kind, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status, string vnetName, string vnetResourceGroupName, string vnetSubnetName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode, string multiSize, valuetype System.Nullable`1&lt;int32&gt; multiRoleCount, valuetype System.Nullable`1&lt;int32&gt; ipsslAddressCount, string databaseEdition, string databaseServiceObjective, valuetype System.Nullable`1&lt;int32&gt; upgradeDomains, string subscriptionId, string dnsSuffix, string lastAction, string lastActionResult, string allowedMultiSizes, string allowedWorkerSizes, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfMachines, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList, valuetype System.Nullable`1&lt;bool&gt; environmentIsHealthy, string environmentStatus, string resourceGroup, valuetype System.Nullable`1&lt;int32&gt; frontEndScaleFactor, valuetype System.Nullable`1&lt;int32&gt; defaultFrontEndScaleFactor, string apiManagementAccountId, valuetype System.Nullable`1&lt;bool&gt; suspended, valuetype System.Nullable`1&lt;bool&gt; dynamicCacheEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings, class System.Collections.Generic.IList`1&lt;string&gt; userWhitelistedIpRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.#ctor(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.WorkerPool},System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.StampCapacity},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NameValuePair},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (appServiceEnvironmentPatchResourceName As String, location As String, virtualNetwork As VirtualNetworkProfile, workerPools As IList(Of WorkerPool), Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of HostingEnvironmentStatus) = null, Optional vnetName As String = null, Optional vnetResourceGroupName As String = null, Optional vnetSubnetName As String = null, Optional internalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode) = null, Optional multiSize As String = null, Optional multiRoleCount As Nullable(Of Integer) = null, Optional ipsslAddressCount As Nullable(Of Integer) = null, Optional databaseEdition As String = null, Optional databaseServiceObjective As String = null, Optional upgradeDomains As Nullable(Of Integer) = null, Optional subscriptionId As String = null, Optional dnsSuffix As String = null, Optional lastAction As String = null, Optional lastActionResult As String = null, Optional allowedMultiSizes As String = null, Optional allowedWorkerSizes As String = null, Optional maximumNumberOfMachines As Nullable(Of Integer) = null, Optional vipMappings As IList(Of VirtualIPMapping) = null, Optional environmentCapacities As IList(Of StampCapacity) = null, Optional networkAccessControlList As IList(Of NetworkAccessControlEntry) = null, Optional environmentIsHealthy As Nullable(Of Boolean) = null, Optional environmentStatus As String = null, Optional resourceGroup As String = null, Optional frontEndScaleFactor As Nullable(Of Integer) = null, Optional defaultFrontEndScaleFactor As Nullable(Of Integer) = null, Optional apiManagementAccountId As String = null, Optional suspended As Nullable(Of Boolean) = null, Optional dynamicCacheEnabled As Nullable(Of Boolean) = null, Optional clusterSettings As IList(Of NameValuePair) = null, Optional userWhitelistedIpRanges As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource : string * string * Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * string * string * string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource (appServiceEnvironmentPatchResourceName, location, virtualNetwork, workerPools, id, name, kind, type, provisioningState, status, vnetName, vnetResourceGroupName, vnetSubnetName, internalLoadBalancingMode, multiSize, multiRoleCount, ipsslAddressCount, databaseEdition, databaseServiceObjective, upgradeDomains, subscriptionId, dnsSuffix, lastAction, lastActionResult, allowedMultiSizes, allowedWorkerSizes, maximumNumberOfMachines, vipMappings, environmentCapacities, networkAccessControlList, environmentIsHealthy, environmentStatus, resourceGroup, frontEndScaleFactor, defaultFrontEndScaleFactor, apiManagementAccountId, suspended, dynamicCacheEnabled, clusterSettings, userWhitelistedIpRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="appServiceEnvironmentPatchResourceName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="virtualNetwork" Type="Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile" />
        <Parameter Name="workerPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vnetResourceGroupName" Type="System.String" />
        <Parameter Name="vnetSubnetName" Type="System.String" />
        <Parameter Name="internalLoadBalancingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;" />
        <Parameter Name="multiSize" Type="System.String" />
        <Parameter Name="multiRoleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="ipsslAddressCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="databaseServiceObjective" Type="System.String" />
        <Parameter Name="upgradeDomains" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="dnsSuffix" Type="System.String" />
        <Parameter Name="lastAction" Type="System.String" />
        <Parameter Name="lastActionResult" Type="System.String" />
        <Parameter Name="allowedMultiSizes" Type="System.String" />
        <Parameter Name="allowedWorkerSizes" Type="System.String" />
        <Parameter Name="maximumNumberOfMachines" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="vipMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" />
        <Parameter Name="environmentCapacities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" />
        <Parameter Name="networkAccessControlList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;" />
        <Parameter Name="environmentIsHealthy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="environmentStatus" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="frontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultFrontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="apiManagementAccountId" Type="System.String" />
        <Parameter Name="suspended" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dynamicCacheEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clusterSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;" />
        <Parameter Name="userWhitelistedIpRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="appServiceEnvironmentPatchResourceName"><span data-ttu-id="66413-103">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="66413-103">Name of the App Service Environment.</span></span></param>
        <param name="location"><span data-ttu-id="66413-104">App Service 環境の場所。"West US"です。</span><span class="sxs-lookup"><span data-stu-id="66413-104">Location of the App Service Environment, e.g. "West US".</span></span></param>
        <param name="virtualNetwork"><span data-ttu-id="66413-105">仮想ネットワークの説明です。</span><span class="sxs-lookup"><span data-stu-id="66413-105">Description of the Virtual Network.</span></span></param>
        <param name="workerPools"><span data-ttu-id="66413-106">ワーカー サイズ Id、VM サイズ、および各プールでワーカーの数のワーカー プールの説明です。</span><span class="sxs-lookup"><span data-stu-id="66413-106">Description of worker pools with worker size IDs, VM sizes, and number of workers in each pool.</span></span></param>
        <param name="id"><span data-ttu-id="66413-107">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="66413-107">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="66413-108">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="66413-108">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="66413-109">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="66413-109">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="66413-110">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="66413-110">Resource type.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="66413-111">App Service 環境の状態を準備しています。</span><span class="sxs-lookup"><span data-stu-id="66413-111">Provisioning state of the App Service Environment.</span></span> <span data-ttu-id="66413-112">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="66413-112">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <param name="status"><span data-ttu-id="66413-113">App Service 環境の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="66413-113">Current status of the App Service Environment.</span></span>
            <span data-ttu-id="66413-114">使用可能な値が含まれます: 'を準備する'、'準備完了'、'スケーリング'、'削除'</span><span class="sxs-lookup"><span data-stu-id="66413-114">Possible values include: 'Preparing', 'Ready', 'Scaling', 'Deleting'</span></span></param>
        <param name="vnetName"><span data-ttu-id="66413-115">App Service 環境の仮想ネットワークの名前。</span><span class="sxs-lookup"><span data-stu-id="66413-115">Name of the Virtual Network for the App Service Environment.</span></span></param>
        <param name="vnetResourceGroupName"><span data-ttu-id="66413-116">仮想ネットワークのリソース グループです。</span><span class="sxs-lookup"><span data-stu-id="66413-116">Resource group of the Virtual Network.</span></span></param>
        <param name="vnetSubnetName"><span data-ttu-id="66413-117">仮想ネットワークのサブネットです。</span><span class="sxs-lookup"><span data-stu-id="66413-117">Subnet of the Virtual Network.</span></span></param>
        <param name="internalLoadBalancingMode"><span data-ttu-id="66413-118">App Service 環境の仮想ネットワークで内部的に機能するには、どのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="66413-118">Specifies which endpoints to serve internally in the Virtual Network for the App Service Environment.</span></span> <span data-ttu-id="66413-119">使用可能な値が含まれます 'None'、'Web'、'公開'。</span><span class="sxs-lookup"><span data-stu-id="66413-119">Possible values include: 'None', 'Web', 'Publishing'</span></span></param>
        <param name="multiSize"><span data-ttu-id="66413-120">フロント エンドの VM サイズ例。「中」、"Large"です。</span><span class="sxs-lookup"><span data-stu-id="66413-120">Front-end VM size, e.g. "Medium", "Large".</span></span></param>
        <param name="multiRoleCount"><span data-ttu-id="66413-121">フロント エンド インスタンスの数。</span><span class="sxs-lookup"><span data-stu-id="66413-121">Number of front-end instances.</span></span></param>
        <param name="ipsslAddressCount"><span data-ttu-id="66413-122">App Service 環境の予約済みの IP SSL アドレスの数。</span><span class="sxs-lookup"><span data-stu-id="66413-122">Number of IP SSL addresses reserved for the App Service Environment.</span></span></param>
        <param name="databaseEdition"><span data-ttu-id="66413-123">App Service 環境のデータベースの例: メタデータのエディション「標準」です。</span><span class="sxs-lookup"><span data-stu-id="66413-123">Edition of the metadata database for the App Service Environment, e.g. "Standard".</span></span></param>
        <param name="databaseServiceObjective"><span data-ttu-id="66413-124">サービスのメタデータ データベースの目標を App Service 環境例。"S0"です。</span><span class="sxs-lookup"><span data-stu-id="66413-124">Service objective of the metadata database for the App Service Environment, e.g. "S0".</span></span></param>
        <param name="upgradeDomains"><span data-ttu-id="66413-125">App Service Environment のアップグレード ドメインの数。</span><span class="sxs-lookup"><span data-stu-id="66413-125">Number of upgrade domains of the App Service Environment.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="66413-126">App Service 環境のサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="66413-126">Subscription of the App Service Environment.</span></span></param>
        <param name="dnsSuffix"><span data-ttu-id="66413-127">App Service 環境の DNS サフィックス。</span><span class="sxs-lookup"><span data-stu-id="66413-127">DNS suffix of the App Service Environment.</span></span></param>
        <param name="lastAction"><span data-ttu-id="66413-128">App Service 環境の最後の展開の操作です。</span><span class="sxs-lookup"><span data-stu-id="66413-128">Last deployment action on the App Service Environment.</span></span></param>
        <param name="lastActionResult"><span data-ttu-id="66413-129">App Service 環境の最後の展開の操作の結果です。</span><span class="sxs-lookup"><span data-stu-id="66413-129">Result of the last deployment action on the App Service Environment.</span></span></param>
        <param name="allowedMultiSizes"><span data-ttu-id="66413-130">コンマの一覧には、フロント エンドは許可されている VM のサイズを記述する文字列が区切られます。</span><span class="sxs-lookup"><span data-stu-id="66413-130">List of comma separated strings describing which VM sizes are allowed for front-ends.</span></span></param>
        <param name="allowedWorkerSizes"><span data-ttu-id="66413-131">コンマの一覧には、ワーカーは許可されている VM のサイズを記述する文字列が区切られます。</span><span class="sxs-lookup"><span data-stu-id="66413-131">List of comma separated strings describing which VM sizes are allowed for workers.</span></span></param>
        <param name="maximumNumberOfMachines"><span data-ttu-id="66413-132">App Service Environment で Vm の最大数。</span><span class="sxs-lookup"><span data-stu-id="66413-132">Maximum number of VMs in the App Service Environment.</span></span></param>
        <param name="vipMappings"><span data-ttu-id="66413-133">IP SSL のマッピングを App Service 環境の説明です。</span><span class="sxs-lookup"><span data-stu-id="66413-133">Description of IP SSL mapping for the App Service Environment.</span></span></param>
        <param name="environmentCapacities"><span data-ttu-id="66413-134">現在の合計、使用、および使用可能なワーカーの容量。</span><span class="sxs-lookup"><span data-stu-id="66413-134">Current total, used, and available worker capacities.</span></span></param>
        <param name="networkAccessControlList"><span data-ttu-id="66413-135">App Service 環境へのトラフィックを制御するためのアクセス制御リストです。</span><span class="sxs-lookup"><span data-stu-id="66413-135">Access control list for controlling traffic to the App Service Environment.</span></span></param>
        <param name="environmentIsHealthy"><span data-ttu-id="66413-136">App Service 環境が正常かどうかを示す true または false です。</span><span class="sxs-lookup"><span data-stu-id="66413-136">True/false indicating whether the App Service Environment is healthy.</span></span></param>
        <param name="environmentStatus"><span data-ttu-id="66413-137">App Service 環境の最後のチェックの結果を含むに関する詳細なメッセージです。</span><span class="sxs-lookup"><span data-stu-id="66413-137">Detailed message about with results of the last check of the App Service Environment.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="66413-138">App Service 環境のリソース グループです。</span><span class="sxs-lookup"><span data-stu-id="66413-138">Resource group of the App Service Environment.</span></span></param>
        <param name="frontEndScaleFactor"><span data-ttu-id="66413-139">フロント エンドのスケール ファクター。</span><span class="sxs-lookup"><span data-stu-id="66413-139">Scale factor for front-ends.</span></span></param>
        <param name="defaultFrontEndScaleFactor"><span data-ttu-id="66413-140">フロント エンドに対して既定のスケール ファクター。</span><span class="sxs-lookup"><span data-stu-id="66413-140">Default Scale Factor for FrontEnds.</span></span></param>
        <param name="apiManagementAccountId"><span data-ttu-id="66413-141">API 管理アカウントが App Service 環境に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="66413-141">API Management Account associated with the App Service Environment.</span></span></param>
        <param name="suspended"><span data-ttu-id="66413-142">&lt;コード&gt;true&lt;/code&gt; App Service 環境が中断されている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="66413-142">&lt;code&gt;true&lt;/code&gt; if the App Service Environment is suspended; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="66413-143">環境を中断することができますなどと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="66413-143">The environment can be suspended, e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span></param>
        <param name="dynamicCacheEnabled"><span data-ttu-id="66413-144">App Service 環境が中断されているかどうかを示す true または false です。</span><span class="sxs-lookup"><span data-stu-id="66413-144">True/false indicating whether the App Service Environment is suspended.</span></span> <span data-ttu-id="66413-145">環境を指定できます中断などと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="66413-145">The environment can be suspended e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span></param>
        <param name="clusterSettings"><span data-ttu-id="66413-146">App Service 環境の動作を変更するためのカスタム設定。</span><span class="sxs-lookup"><span data-stu-id="66413-146">Custom settings for changing the behavior of the App Service Environment.</span></span></param>
        <param name="userWhitelistedIpRanges"><span data-ttu-id="66413-147">ユーザーを ASE db のホワイト リスト ip の範囲を追加します。</span><span class="sxs-lookup"><span data-stu-id="66413-147">User added ip ranges to whitelist on ASE db</span></span></param>
        <summary>
            <span data-ttu-id="66413-148">AppServiceEnvironmentPatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66413-148">Initializes a new instance of the AppServiceEnvironmentPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedMultiSizes">
      <MemberSignature Language="C#" Value="public string AllowedMultiSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedMultiSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AllowedMultiSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedMultiSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedMultiSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AllowedMultiSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedMultiSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-149">コンマ区切りの文字列の一覧を取得フロント エンドの VM サイズが許可されている記述します。</span><span class="sxs-lookup"><span data-stu-id="66413-149">Gets list of comma separated strings describing which VM sizes are allowed for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedWorkerSizes">
      <MemberSignature Language="C#" Value="public string AllowedWorkerSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedWorkerSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AllowedWorkerSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedWorkerSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedWorkerSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AllowedWorkerSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedWorkerSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-150">取得コンマ区切りの文字列の一覧の記述作業者の VM サイズが許可されます。</span><span class="sxs-lookup"><span data-stu-id="66413-150">Gets list of comma separated strings describing which VM sizes are allowed for workers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiManagementAccountId">
      <MemberSignature Language="C#" Value="public string ApiManagementAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiManagementAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ApiManagementAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiManagementAccountId As String" />
      <MemberSignature Language="F#" Value="member this.ApiManagementAccountId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ApiManagementAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiManagementAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-151">取得または App Service 環境に関連付けられている API 管理アカウントを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-151">Gets or sets API Management Account associated with the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironmentPatchResourceName">
      <MemberSignature Language="C#" Value="public string AppServiceEnvironmentPatchResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServiceEnvironmentPatchResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AppServiceEnvironmentPatchResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServiceEnvironmentPatchResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironmentPatchResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.AppServiceEnvironmentPatchResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-152">取得または App Service 環境の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-152">Gets or sets name of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ClusterSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ClusterSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ClusterSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-153">取得または App Service 環境の動作を変更するためのカスタム設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-153">Gets or sets custom settings for changing the behavior of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-154">例: App Service 環境のメタデータ データベースのエディションを取得します。「標準」です。</span><span class="sxs-lookup"><span data-stu-id="66413-154">Gets edition of the metadata database for the App Service Environment, e.g. "Standard".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseServiceObjective">
      <MemberSignature Language="C#" Value="public string DatabaseServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DatabaseServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseServiceObjective : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DatabaseServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-155">例: メタデータ データベースのサービス目標を App Service 環境の取得します。"S0"です。</span><span class="sxs-lookup"><span data-stu-id="66413-155">Gets service objective of the metadata database for the App Service Environment, e.g. "S0".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultFrontEndScaleFactor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultFrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DefaultFrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultFrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultFrontEndScaleFactor : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DefaultFrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultFrontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-156">フロント エンドに対して既定のスケール ファクターを取得。</span><span class="sxs-lookup"><span data-stu-id="66413-156">Gets default Scale Factor for FrontEnds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSuffix">
      <MemberSignature Language="C#" Value="public string DnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.DnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-157">取得または App Service 環境の DNS サフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-157">Gets or sets DNS suffix of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCacheEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DynamicCacheEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DynamicCacheEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DynamicCacheEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCacheEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DynamicCacheEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.DynamicCacheEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicCacheEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-158">取得または App Service 環境が中断されているかどうかを示す true または false を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-158">Gets or sets true/false indicating whether the App Service Environment is suspended.</span></span> <span data-ttu-id="66413-159">環境を指定できます中断などと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="66413-159">The environment can be suspended e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentCapacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentCapacities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentCapacities As IList(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentCapacities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentCapacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentCapacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-160">現在の合計、使用、および使用可能なワーカーの容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-160">Gets current total, used, and available worker capacities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentIsHealthy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnvironmentIsHealthy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnvironmentIsHealthy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentIsHealthy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentIsHealthy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentIsHealthy : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentIsHealthy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentIsHealthy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-161">App Service 環境が正常かどうかを示す true または false を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-161">Gets true/false indicating whether the App Service Environment is healthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentStatus">
      <MemberSignature Language="C#" Value="public string EnvironmentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnvironmentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentStatus As String" />
      <MemberSignature Language="F#" Value="member this.EnvironmentStatus : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.EnvironmentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-162">取得についての詳細メッセージの App Service 環境の最後のチェックの結果。</span><span class="sxs-lookup"><span data-stu-id="66413-162">Gets detailed message about with results of the last check of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontEndScaleFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.FrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontEndScaleFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.FrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-163">取得またはフロント エンドのスケール ファクターを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-163">Gets or sets scale factor for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalLoadBalancingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.InternalLoadBalancingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode)" />
      <MemberSignature Language="F#" Value="member this.InternalLoadBalancingMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.InternalLoadBalancingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.internalLoadBalancingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-164">取得または設定は、App Service 環境の仮想ネットワークで内部的に機能するには、どのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="66413-164">Gets or sets specifies which endpoints to serve internally in the Virtual Network for the App Service Environment.</span></span> <span data-ttu-id="66413-165">使用可能な値が含まれます 'None'、'Web'、'公開'。</span><span class="sxs-lookup"><span data-stu-id="66413-165">Possible values include: 'None', 'Web', 'Publishing'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsslAddressCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IpsslAddressCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IpsslAddressCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.IpsslAddressCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsslAddressCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IpsslAddressCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.IpsslAddressCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipsslAddressCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-166">取得または予約済みの App Service 環境の IP SSL アドレスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-166">Gets or sets number of IP SSL addresses reserved for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAction">
      <MemberSignature Language="C#" Value="public string LastAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.LastAction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAction As String" />
      <MemberSignature Language="F#" Value="member this.LastAction : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.LastAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-167">取得の最後の App Service 環境の展開操作します。</span><span class="sxs-lookup"><span data-stu-id="66413-167">Gets last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActionResult">
      <MemberSignature Language="C#" Value="public string LastActionResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastActionResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.LastActionResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActionResult As String" />
      <MemberSignature Language="F#" Value="member this.LastActionResult : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.LastActionResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastActionResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-168">App Service 環境の最後の展開の操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-168">Gets result of the last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-169">取得またはなどの App Service 環境の場所を設定"West US"です。</span><span class="sxs-lookup"><span data-stu-id="66413-169">Gets or sets location of the App Service Environment, e.g. "West US".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfMachines">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MaximumNumberOfMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfMachines As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfMachines : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MaximumNumberOfMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfMachines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-170">App Service Environment で Vm の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-170">Gets maximum number of VMs in the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiRoleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MultiRoleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MultiRoleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MultiRoleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiRoleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MultiRoleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MultiRoleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiRoleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-171">取得またはフロント エンド インスタンスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-171">Gets or sets number of front-end instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiSize">
      <MemberSignature Language="C#" Value="public string MultiSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MultiSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MultiSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiSize As String" />
      <MemberSignature Language="F#" Value="member this.MultiSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.MultiSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-172">例: フロント エンドの VM サイズの設定を取得または「中」、"Large"です。</span><span class="sxs-lookup"><span data-stu-id="66413-172">Gets or sets front-end VM size, e.g. "Medium", "Large".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAccessControlList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.NetworkAccessControlList" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAccessControlList As IList(Of NetworkAccessControlEntry)" />
      <MemberSignature Language="F#" Value="member this.NetworkAccessControlList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.NetworkAccessControlList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAccessControlList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-173">取得または App Service 環境へのトラフィックを制御するためのアクセス制御リストを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-173">Gets or sets access control list for controlling traffic to the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-174">App Service 環境の状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-174">Gets provisioning state of the App Service Environment.</span></span> <span data-ttu-id="66413-175">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="66413-175">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.ResourceGroup" />
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
            <span data-ttu-id="66413-176">App Service 環境のリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-176">Gets resource group of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of HostingEnvironmentStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-177">App Service 環境の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-177">Gets current status of the App Service Environment.</span></span> <span data-ttu-id="66413-178">使用可能な値が含まれます: 'を準備する'、'準備完了'、'スケーリング'、'削除'</span><span class="sxs-lookup"><span data-stu-id="66413-178">Possible values include: 'Preparing', 'Ready', 'Scaling', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-179">App Service 環境のサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-179">Gets subscription of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspended">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Suspended { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Suspended" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Suspended" />
      <MemberSignature Language="VB.NET" Value="Public Property Suspended As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Suspended : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Suspended" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspended")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-180">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service 環境が中断されている、それ以外の場合は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="66413-180">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the App Service Environment is suspended; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="66413-181">環境を中断することができますなどと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="66413-181">The environment can be suspended, e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeDomains")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-182">App Service Environment のアップグレード ドメインの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-182">Gets number of upgrade domains of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserWhitelistedIpRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; UserWhitelistedIpRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; UserWhitelistedIpRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.UserWhitelistedIpRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property UserWhitelistedIpRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.UserWhitelistedIpRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.UserWhitelistedIpRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userWhitelistedIpRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-183">取得または追加されたユーザーの設定を ASE db のホワイト リスト ip の範囲</span><span class="sxs-lookup"><span data-stu-id="66413-183">Gets or sets user added ip ranges to whitelist on ASE db</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="appServiceEnvironmentPatchResource.Validate " />
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
            <span data-ttu-id="66413-184">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="66413-184">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="66413-185">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="66413-185">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VipMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VipMappings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VipMappings As IList(Of VirtualIPMapping)" />
      <MemberSignature Language="F#" Value="member this.VipMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VipMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vipMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-186">App Service 環境のマッピングの IP SSL の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="66413-186">Gets description of IP SSL mapping for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VirtualNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetwork As VirtualNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualNetwork : Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VirtualNetwork" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetwork")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-187">取得または仮想ネットワークの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-187">Gets or sets description of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetName" />
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
            <span data-ttu-id="66413-188">取得または App Service 環境の仮想ネットワークの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-188">Gets or sets name of the Virtual Network for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceGroupName">
      <MemberSignature Language="C#" Value="public string VnetResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-189">取得または仮想ネットワークのリソース グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-189">Gets or sets resource group of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetSubnetName">
      <MemberSignature Language="C#" Value="public string VnetSubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetSubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetSubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetSubnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetSubnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.VnetSubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetSubnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-190">取得または仮想ネットワークのサブネットを設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-190">Gets or sets subnet of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.WorkerPools" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerPools As IList(Of WorkerPool)" />
      <MemberSignature Language="F#" Value="member this.WorkerPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource.WorkerPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66413-191">取得または各プールでワーカー サイズ Id のワーカー プールの説明、VM サイズ、およびワーカーの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="66413-191">Gets or sets description of worker pools with worker size IDs, VM sizes, and number of workers in each pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>