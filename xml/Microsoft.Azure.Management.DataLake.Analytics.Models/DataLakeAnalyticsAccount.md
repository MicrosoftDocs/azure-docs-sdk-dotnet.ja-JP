<Type Name="DataLakeAnalyticsAccount" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccount : Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccount extends Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8ef5d-101">Data Lake Analytics アカウント オブジェクト、名前付きの Data Lake Analytics アカウントに関連付けられているすべての情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-101">A Data Lake Analytics account object, containing all information associated with the named Data Lake Analytics account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-102">DataLakeAnalyticsAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-102">Initializes a new instance of the DataLakeAnalyticsAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount (string location, string defaultDataLakeStoreAccount, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null, Nullable&lt;int&gt; maxDegreeOfParallelism = null, Nullable&lt;int&gt; queryStoreRetention = null, Nullable&lt;int&gt; maxJobCount = null, Nullable&lt;int&gt; systemMaxDegreeOfParallelism = null, Nullable&lt;int&gt; systemMaxJobCount = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules = null, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string defaultDataLakeStoreAccount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; queryStoreRetention, valuetype System.Nullable`1&lt;int32&gt; maxJobCount, valuetype System.Nullable`1&lt;int32&gt; systemMaxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; systemMaxJobCount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, defaultDataLakeStoreAccount As String, dataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null, Optional maxDegreeOfParallelism As Nullable(Of Integer) = null, Optional queryStoreRetention As Nullable(Of Integer) = null, Optional maxJobCount As Nullable(Of Integer) = null, Optional systemMaxDegreeOfParallelism As Nullable(Of Integer) = null, Optional systemMaxJobCount As Nullable(Of Integer) = null, Optional storageAccounts As IList(Of StorageAccountInfo) = null, Optional newTier As Nullable(Of TierType) = null, Optional currentTier As Nullable(Of TierType) = null, Optional firewallState As Nullable(Of FirewallState) = null, Optional firewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState) = null, Optional firewallRules As IList(Of FirewallRule) = null, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null, Optional computePolicies As IList(Of ComputePolicyAccountCreateParameters) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount (location, defaultDataLakeStoreAccount, dataLakeStoreAccounts, id, name, type, tags, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId, maxDegreeOfParallelism, queryStoreRetention, maxJobCount, systemMaxDegreeOfParallelism, systemMaxJobCount, storageAccounts, newTier, currentTier, firewallState, firewallAllowAzureIps, firewallRules, maxDegreeOfParallelismPerJob, minPriorityPerJob, computePolicies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="defaultDataLakeStoreAccount" Type="System.String" />
        <Parameter Name="dataLakeStoreAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="maxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="queryStoreRetention" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="currentTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;" />
        <Parameter Name="firewallRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computePolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="8ef5d-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="8ef5d-103">Resource location</span></span></param>
        <param name="defaultDataLakeStoreAccount"><span data-ttu-id="8ef5d-104">既定のデータ lake ストレージ アカウントこの Data Lake Analytics アカウントに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-104">the default data lake storage account associated with this Data Lake Analytics account.</span></span></param>
        <param name="dataLakeStoreAccounts"><span data-ttu-id="8ef5d-105">このアカウントに関連付けられている Data Lake ストレージ アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-105">the list of Data Lake storage accounts associated with this account.</span></span></param>
        <param name="id"><span data-ttu-id="8ef5d-106">リソース Id</span><span class="sxs-lookup"><span data-stu-id="8ef5d-106">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="8ef5d-107">リソース名</span><span class="sxs-lookup"><span data-stu-id="8ef5d-107">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="8ef5d-108">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="8ef5d-108">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="8ef5d-109">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="8ef5d-109">Resource tags</span></span></param>
        <param name="provisioningState"><span data-ttu-id="8ef5d-110">Data Lake Analytics アカウントのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-110">the provisioning status of the Data Lake Analytics account.</span></span> <span data-ttu-id="8ef5d-111">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-111">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span></param>
        <param name="state"><span data-ttu-id="8ef5d-112">Data Lake Analytics アカウントの状態。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-112">the state of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="8ef5d-113">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-113">Possible values include: 'Active', 'Suspended'</span></span></param>
        <param name="creationTime"><span data-ttu-id="8ef5d-114">アカウントの作成時。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-114">the account creation time.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="8ef5d-115">アカウントには、最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-115">the account last modified time.</span></span></param>
        <param name="endpoint"><span data-ttu-id="8ef5d-116">このアカウントの完全な CName エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-116">the full CName endpoint for this account.</span></span></param>
        <param name="accountId"><span data-ttu-id="8ef5d-117">この Data Lake Analytics アカウントに関連付けられている一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-117">The unique identifier associated with this Data Lake Analytics account.</span></span></param>
        <param name="maxDegreeOfParallelism"><span data-ttu-id="8ef5d-118">最大値は、このアカウントの並列処理の次数をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-118">the maximum supported degree of parallelism for this account.</span></span></param>
        <param name="queryStoreRetention"><span data-ttu-id="8ef5d-119">日数をジョブのメタデータは保持されます。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-119">the number of days that job metadata is retained.</span></span></param>
        <param name="maxJobCount"><span data-ttu-id="8ef5d-120">最大値には、同時に、アカウントで実行されているジョブがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-120">the maximum supported jobs running under the account at the same time.</span></span></param>
        <param name="systemMaxDegreeOfParallelism"><span data-ttu-id="8ef5d-121">システムには、このアカウントは、ユーザーがアカウントに対して設定できる並列処理の最大値が制限の並列処理の最大のサポートされている範囲が定義されている.</span><span class="sxs-lookup"><span data-stu-id="8ef5d-121">the system defined maximum supported degree of parallelism for this account, which restricts the maximum value of parallelism the user can set for the account..</span></span></param>
        <param name="systemMaxJobCount"><span data-ttu-id="8ef5d-122">システムでは、同時実行されているアカウントのユーザーが設定できるジョブの最大数を制限するユーザー アカウントが実行されている最大のサポートされているジョブを定義します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-122">the system defined maximum supported jobs running under the account at the same time, which restricts the maximum number of running jobs the user can set for the account.</span></span></param>
        <param name="storageAccounts"><span data-ttu-id="8ef5d-123">このアカウントに関連付けられている Azure Blob ストレージ アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-123">the list of Azure Blob storage accounts associated with this account.</span></span></param>
        <param name="newTier"><span data-ttu-id="8ef5d-124">コミットメントの層を次の月です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-124">the commitment tier for the next month.</span></span>
            <span data-ttu-id="8ef5d-125">使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-125">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span></param>
        <param name="currentTier"><span data-ttu-id="8ef5d-126">現在の月の使用中コミットメント層です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-126">the commitment tier in use for the current month.</span></span> <span data-ttu-id="8ef5d-127">使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-127">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span></param>
        <param name="firewallState"><span data-ttu-id="8ef5d-128">この Data Lake Analytics アカウントの IP アドレスをファイアウォールの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-128">The current state of the IP address firewall for this Data Lake Analytics account.</span></span> <span data-ttu-id="8ef5d-129">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-129">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallAllowAzureIps"><span data-ttu-id="8ef5d-130">ファイアウォールを介して Azure 内で元の ip アドレスを許可するかの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-130">The current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span>
            <span data-ttu-id="8ef5d-131">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-131">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="8ef5d-132">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-132">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallRules"><span data-ttu-id="8ef5d-133">この Data Lake Analytics アカウントに関連付けられているファイアウォール ルールの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-133">The list of firewall rules associated with this Data Lake Analytics account.</span></span></param>
        <param name="maxDegreeOfParallelismPerJob"><span data-ttu-id="8ef5d-134">最大値は、このアカウント (job) あたりの並列処理の次数をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-134">the maximum supported degree of parallelism per job for this account.</span></span></param>
        <param name="minPriorityPerJob"><span data-ttu-id="8ef5d-135">最小値は、このアカウントごとのジョブの優先度をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-135">the minimum supported priority per job for this account.</span></span></param>
        <param name="computePolicies"><span data-ttu-id="8ef5d-136">このアカウントを作成するコンピューティング ポリシーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-136">the list of compute policies to create in this account.</span></span></param>
        <summary>
            <span data-ttu-id="8ef5d-137">DataLakeAnalyticsAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-137">Initializes a new instance of the DataLakeAnalyticsAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-138">この Data Lake Analytics アカウントに関連付けられている一意の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-138">Gets the unique identifier associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputePolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputePolicies As IList(Of ComputePolicyAccountCreateParameters)" />
      <MemberSignature Language="F#" Value="member this.ComputePolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computePolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-139">取得またはこのアカウントを作成するコンピューティング ポリシーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-139">Gets or sets the list of compute policies to create in this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-140">アカウントの作成時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-140">Gets the account creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.CurrentTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-141">現在の月の使用のコミットメント層を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-141">Gets the commitment tier in use for the current month.</span></span> <span data-ttu-id="8ef5d-142">使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-142">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLakeStoreAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-143">取得またはこのアカウントに関連付けられている Data Lake ストレージ アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-143">Gets or sets the list of Data Lake storage accounts associated with this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDataLakeStoreAccount">
      <MemberSignature Language="C#" Value="public string DefaultDataLakeStoreAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultDataLakeStoreAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDataLakeStoreAccount As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDataLakeStoreAccount : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultDataLakeStoreAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-144">取得またはこの Data Lake Analytics アカウントに関連付けられている既定の data lake ストレージ アカウントを設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-144">Gets or sets the default data lake storage account associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-145">このアカウントに、完全な CName エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-145">Gets the full CName endpoint for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallAllowAzureIps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-146">取得または許可をファイアウォール経由の Azure 内で元の ip アドレスを許可するかの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-146">Gets or sets the current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span> <span data-ttu-id="8ef5d-147">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-147">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="8ef5d-148">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-148">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallRules As IList(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-149">取得またはこの Data Lake Analytics アカウントに関連付けられているファイアウォール ルールの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-149">Gets or sets the list of firewall rules associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-150">取得またはこの Data Lake Analytics アカウントの IP アドレスをファイアウォールの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-150">Gets or sets the current state of the IP address firewall for this Data Lake Analytics account.</span></span> <span data-ttu-id="8ef5d-151">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-151">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-152">アカウントの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-152">Gets the account last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-153">取得またはこのアカウントの並列処理のサポートされている最大限度を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-153">Gets or sets the maximum supported degree of parallelism for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-154">取得またはこのアカウントのジョブあたりの並列処理のサポートされている最大限度を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-154">Gets or sets the maximum supported degree of parallelism per job for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxJobCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxJobCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-155">取得または同時に、アカウントで実行されている最大のサポートされているジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-155">Gets or sets the maximum supported jobs running under the account at the same time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-156">取得またはごとのジョブがこのアカウントの最小のサポートされている優先度を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-156">Gets or sets the minimum supported priority per job for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.newTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-157">取得または次の月のコミットメント層を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-157">Gets or sets the commitment tier for the next month.</span></span> <span data-ttu-id="8ef5d-158">使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-158">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-159">Data Lake Analytics アカウントのプロビジョニング状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-159">Gets the provisioning status of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="8ef5d-160">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-160">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStoreRetention">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; QueryStoreRetention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; QueryStoreRetention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStoreRetention As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.QueryStoreRetention : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queryStoreRetention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-161">取得または設定の日数をジョブのメタデータは保持されます。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-161">Gets or sets the number of days that job metadata is retained.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-162">Data Lake Analytics アカウントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-162">Gets the state of the Data Lake Analytics account.</span></span> <span data-ttu-id="8ef5d-163">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="8ef5d-163">Possible values include: 'Active', 'Suspended'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-164">取得またはこのアカウントに関連付けられている Azure Blob ストレージ アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-164">Gets or sets the list of Azure Blob storage accounts associated with this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxDegreeOfParallelism { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxDegreeOfParallelism : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-165">このアカウントは、ユーザーがアカウントに対して設定できる並列処理の最大値を制限、システム定義最大サポートされている並列処理の次数を取得する.</span><span class="sxs-lookup"><span data-stu-id="8ef5d-165">Gets the system defined maximum supported degree of parallelism for this account, which restricts the maximum value of parallelism the user can set for the account..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxJobCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxJobCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-166">同時実行されているジョブ、ユーザーの最大数を制限するアカウントで実行されている最大の定義済みのサポートされているジョブがアカウントに対して設定できる、システムを取得します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-166">Gets the system defined maximum supported jobs running under the account at the same time, which restricts the maximum number of running jobs the user can set for the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ef5d-167">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-167">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8ef5d-168">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8ef5d-168">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>