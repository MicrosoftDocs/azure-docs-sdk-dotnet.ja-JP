<Type Name="DataLakeStoreAccount" FullName="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount">
  <TypeSignature Language="C#" Value="public class DataLakeStoreAccount : Microsoft.Azure.Management.DataLake.Store.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreAccount extends Microsoft.Azure.Management.DataLake.Store.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ca7fc-101">Data Lake Store アカウント情報</span><span class="sxs-lookup"><span data-stu-id="ca7fc-101">Data Lake Store account information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-102">DataLakeStoreAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-102">Initializes a new instance of the DataLakeStoreAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccount (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity identity = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; encryptionState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; encryptionProvisioningState = null, Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig encryptionConfig = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; firewallRules = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; trustedIdProviders = null, string defaultGroup = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; currentTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity identity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; encryptionState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; encryptionProvisioningState, class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig encryptionConfig, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; firewallRules, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; trustedIdProviders, string defaultGroup, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; currentTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState},Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider},System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; * Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount (location, id, name, type, tags, identity, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId, encryptionState, encryptionProvisioningState, encryptionConfig, firewallState, firewallRules, trustedIdProviderState, trustedIdProviders, defaultGroup, newTier, currentTier, firewallAllowAzureIps)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="encryptionState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt;" />
        <Parameter Name="encryptionProvisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;" />
        <Parameter Name="encryptionConfig" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt;" />
        <Parameter Name="firewallRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" />
        <Parameter Name="trustedIdProviderState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt;" />
        <Parameter Name="trustedIdProviders" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" />
        <Parameter Name="defaultGroup" Type="System.String" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" />
        <Parameter Name="currentTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="ca7fc-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="ca7fc-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="ca7fc-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="ca7fc-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="ca7fc-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="ca7fc-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="ca7fc-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="ca7fc-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="ca7fc-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="ca7fc-107">Resource tags</span></span></param>
        <param name="identity"><span data-ttu-id="ca7fc-108">Key Vault 暗号化 id、存在する場合。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-108">The Key Vault encryption identity, if any.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="ca7fc-109">Data Lake Store アカウントのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-109">the provisioning status of the Data Lake Store account.</span></span> <span data-ttu-id="ca7fc-110">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-110">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span></param>
        <param name="state"><span data-ttu-id="ca7fc-111">Data Lake Store アカウントの状態。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-111">the state of the Data Lake Store account.</span></span>
            <span data-ttu-id="ca7fc-112">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-112">Possible values include: 'Active', 'Suspended'</span></span></param>
        <param name="creationTime"><span data-ttu-id="ca7fc-113">アカウントの作成時。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-113">the account creation time.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="ca7fc-114">アカウントには、最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-114">the account last modified time.</span></span></param>
        <param name="endpoint"><span data-ttu-id="ca7fc-115">このアカウントの完全な CName エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-115">the full CName endpoint for this account.</span></span></param>
        <param name="accountId"><span data-ttu-id="ca7fc-116">この Data Lake Store アカウントに関連付けられている一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-116">The unique identifier associated with this Data Lake Store account.</span></span></param>
        <param name="encryptionState"><span data-ttu-id="ca7fc-117">この Data Lake の暗号化の現在の状態は、アカウントを保存します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-117">The current state of encryption for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-118">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-118">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="encryptionProvisioningState"><span data-ttu-id="ca7fc-119">暗号化は、この Data Lake store アカウントのプロビジョニングの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-119">The current state of encryption provisioning for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-120">使用可能な値が含まれます: '作成中'、'成功'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-120">Possible values include: 'Creating', 'Succeeded'</span></span></param>
        <param name="encryptionConfig"><span data-ttu-id="ca7fc-121">Key Vault の暗号化構成します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-121">The Key Vault encryption configuration.</span></span></param>
        <param name="firewallState"><span data-ttu-id="ca7fc-122">この Data Lake の IP アドレスをファイアウォールの現在の状態は、アカウントを保存します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-122">The current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-123">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-123">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallRules"><span data-ttu-id="ca7fc-124">この Data Lake store アカウントに関連付けられているファイアウォール ルールの一覧です。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-124">The list of firewall rules associated with this Data Lake store account.</span></span></param>
        <param name="trustedIdProviderState"><span data-ttu-id="ca7fc-125">この Data Lake の信頼された id プロバイダーの機能の現在の状態は、アカウントを保存します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-125">The current state of the trusted identity provider feature for this Data Lake store account.</span></span>
            <span data-ttu-id="ca7fc-126">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-126">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="trustedIdProviders"><span data-ttu-id="ca7fc-127">この Data Lake store アカウントに関連付けられている信頼された id プロバイダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-127">The list of trusted identity providers associated with this Data Lake store account.</span></span></param>
        <param name="defaultGroup"><span data-ttu-id="ca7fc-128">すべての新しいフォルダーと、Data Lake Store アカウントに作成されるファイルの既定の所有者グループ。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-128">the default owner group for all new folders and files created in the Data Lake Store account.</span></span></param>
        <param name="newTier"><span data-ttu-id="ca7fc-129">次の月に使用するコミットメント層です。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-129">the commitment tier to use for next month.</span></span>
            <span data-ttu-id="ca7fc-130">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-130">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span></param>
        <param name="currentTier"><span data-ttu-id="ca7fc-131">現在の月の使用中コミットメント層です。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-131">the commitment tier in use for the current month.</span></span> <span data-ttu-id="ca7fc-132">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-132">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span></param>
        <param name="firewallAllowAzureIps"><span data-ttu-id="ca7fc-133">ファイアウォールを介して Azure 内で元の ip アドレスを許可するかの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-133">The current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span>
            <span data-ttu-id="ca7fc-134">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-134">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="ca7fc-135">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-135">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="ca7fc-136">DataLakeStoreAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-136">Initializes a new instance of the DataLakeStoreAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ca7fc-137">この Data Lake Store アカウントに関連付けられている一意の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-137">Gets the unique identifier associated with this Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ca7fc-138">アカウントの作成時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-138">Gets the account creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; CurrentTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; CurrentTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CurrentTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.CurrentTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CurrentTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-139">現在の月の使用のコミットメント層を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-139">Gets the commitment tier in use for the current month.</span></span> <span data-ttu-id="ca7fc-140">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-140">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultGroup">
      <MemberSignature Language="C#" Value="public string DefaultGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.DefaultGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultGroup As String" />
      <MemberSignature Language="F#" Value="member this.DefaultGroup : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.DefaultGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-141">取得またはすべての新しいフォルダーと、Data Lake Store アカウントに作成されるファイルの既定の所有者のグループを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-141">Gets or sets the default owner group for all new folders and files created in the Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig EncryptionConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig EncryptionConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionConfig As EncryptionConfig" />
      <MemberSignature Language="F#" Value="member this.EncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-142">取得または、Key Vault の暗号化構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-142">Gets or sets the Key Vault encryption configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; EncryptionProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; EncryptionProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionProvisioningState As Nullable(Of EncryptionProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.EncryptionProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-143">暗号化は、この Data Lake store アカウントのプロビジョニングの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-143">Gets the current state of encryption provisioning for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-144">使用可能な値が含まれます: '作成中'、'成功'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-144">Possible values include: 'Creating', 'Succeeded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; EncryptionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; EncryptionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionState" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionState As Nullable(Of EncryptionState)" />
      <MemberSignature Language="F#" Value="member this.EncryptionState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-145">取得またはこの Data Lake store アカウントの暗号化の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-145">Gets or sets the current state of encryption for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-146">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-146">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ca7fc-147">このアカウントに、完全な CName エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-147">Gets the full CName endpoint for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallAllowAzureIps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallAllowAzureIps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-148">取得または許可をファイアウォール経由の Azure 内で元の ip アドレスを許可するかの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-148">Gets or sets the current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span> <span data-ttu-id="ca7fc-149">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-149">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="ca7fc-150">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-150">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; FirewallRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallRules As IList(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-151">取得またはこの Data Lake store アカウントに関連付けられているファイアウォール ルールの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-151">Gets or sets the list of firewall rules associated with this Data Lake store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-152">取得またはこの Data Lake store アカウントの IP アドレスをファイアウォールの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-152">Gets or sets the current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-153">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-153">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As EncryptionIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-154">取得または、存在する場合は、Key Vault の暗号化の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-154">Gets or sets the Key Vault encryption identity, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ca7fc-155">アカウントの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-155">Gets the account last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.NewTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.newTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-156">取得または次の月に使用するコミットメント層を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-156">Gets or sets the commitment tier to use for next month.</span></span> <span data-ttu-id="ca7fc-157">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-157">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeStoreAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-158">Data Lake Store アカウントのプロビジョニング状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-158">Gets the provisioning status of the Data Lake Store account.</span></span>
            <span data-ttu-id="ca7fc-159">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-159">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeStoreAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-160">Data Lake Store アカウントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-160">Gets the state of the Data Lake Store account.</span></span> <span data-ttu-id="ca7fc-161">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-161">Possible values include: 'Active', 'Suspended'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedIdProviders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; TrustedIdProviders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; TrustedIdProviders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviders" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedIdProviders As IList(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="member this.TrustedIdProviders : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trustedIdProviders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-162">取得またはこの Data Lake store アカウントに関連付けられている信頼された id プロバイダーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-162">Gets or sets the list of trusted identity providers associated with this Data Lake store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedIdProviderState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviderState" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedIdProviderState As Nullable(Of TrustedIdProviderState)" />
      <MemberSignature Language="F#" Value="member this.TrustedIdProviderState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviderState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trustedIdProviderState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-163">取得またはこの Data Lake store アカウントの信頼された id プロバイダーの機能の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-163">Gets or sets the current state of the trusted identity provider feature for this Data Lake store account.</span></span> <span data-ttu-id="ca7fc-164">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="ca7fc-164">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeStoreAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca7fc-165">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-165">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ca7fc-166">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca7fc-166">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>