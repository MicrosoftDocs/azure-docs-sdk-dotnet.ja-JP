<Type Name="DataLakeStoreAccountUpdateParameters" FullName="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters">
  <TypeSignature Language="C#" Value="public class DataLakeStoreAccountUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreAccountUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreAccountUpdateParameters" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccountUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="88a8d-101">Data Lake Store アカウント情報を更新するには</span><span class="sxs-lookup"><span data-stu-id="88a8d-101">Data Lake Store account information to update</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccountUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="88a8d-102">DataLakeStoreAccountUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-102">Initializes a new instance of the DataLakeStoreAccountUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccountUpdateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState = null, string defaultGroup = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null, Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig encryptionConfig = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState, string defaultGroup, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig encryptionConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallState},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState},System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState},Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional firewallState As Nullable(Of FirewallState) = null, Optional trustedIdProviderState As Nullable(Of TrustedIdProviderState) = null, Optional defaultGroup As String = null, Optional newTier As Nullable(Of TierType) = null, Optional firewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState) = null, Optional encryptionConfig As UpdateEncryptionConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; * Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters (tags, firewallState, trustedIdProviderState, defaultGroup, newTier, firewallAllowAzureIps, encryptionConfig)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt;" />
        <Parameter Name="trustedIdProviderState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt;" />
        <Parameter Name="defaultGroup" Type="System.String" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt;" />
        <Parameter Name="encryptionConfig" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="88a8d-103">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="88a8d-103">Resource tags</span></span></param>
        <param name="firewallState"><span data-ttu-id="88a8d-104">この Data Lake の IP アドレスをファイアウォールの現在の状態は、アカウントを保存します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-104">The current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="88a8d-105">ファイアウォールを無効にすると、既存のルールが削除されませんが、ファイアウォールが再び有効にするまで、無視だけ。</span><span class="sxs-lookup"><span data-stu-id="88a8d-105">Disabling the firewall does not remove existing rules, they will just be ignored until the firewall is re-enabled.</span></span> <span data-ttu-id="88a8d-106">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-106">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="trustedIdProviderState"><span data-ttu-id="88a8d-107">この Data Lake の信頼された id プロバイダーの機能の現在の状態は、アカウントを保存します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-107">The current state of the trusted identity provider feature for this Data Lake store account.</span></span>
            <span data-ttu-id="88a8d-108">信頼できる id プロバイダーの機能を無効にすると、プロバイダーが削除されませんが、この機能を再び有効にするまで、無視だけ。</span><span class="sxs-lookup"><span data-stu-id="88a8d-108">Disabling trusted identity provider functionality does not remove the providers, they will just be ignored until this feature is re-enabled.</span></span> <span data-ttu-id="88a8d-109">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-109">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="defaultGroup"><span data-ttu-id="88a8d-110">すべての新しいフォルダーと、Data Lake Store アカウントに作成されるファイルの既定の所有者グループ。</span><span class="sxs-lookup"><span data-stu-id="88a8d-110">the default owner group for all new folders and files created in the Data Lake Store account.</span></span></param>
        <param name="newTier"><span data-ttu-id="88a8d-111">次の月に使用するコミットメント層です。</span><span class="sxs-lookup"><span data-stu-id="88a8d-111">the commitment tier to use for next month.</span></span>
            <span data-ttu-id="88a8d-112">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="88a8d-112">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span></param>
        <param name="firewallAllowAzureIps"><span data-ttu-id="88a8d-113">ファイアウォールを介して Azure 内で元の ip アドレスを許可するかの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="88a8d-113">The current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span>
            <span data-ttu-id="88a8d-114">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="88a8d-114">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="88a8d-115">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-115">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="encryptionConfig"><span data-ttu-id="88a8d-116">ユーザーに管理される Key Vault のキーの回転を使用します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-116">Used for rotation of user managed Key Vault keys.</span></span> <span data-ttu-id="88a8d-117">ユーザーが管理されている暗号化の Key Vault のキーを回転させるだけ使用できます。</span><span class="sxs-lookup"><span data-stu-id="88a8d-117">Can only be used to rotate a user managed encryption Key Vault key.</span></span></param>
        <summary>
            <span data-ttu-id="88a8d-118">DataLakeStoreAccountUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-118">Initializes a new instance of the DataLakeStoreAccountUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultGroup">
      <MemberSignature Language="C#" Value="public string DefaultGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.DefaultGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultGroup As String" />
      <MemberSignature Language="F#" Value="member this.DefaultGroup : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.DefaultGroup" />
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
            <span data-ttu-id="88a8d-119">取得またはすべての新しいフォルダーと、Data Lake Store アカウントに作成されるファイルの既定の所有者のグループを設定します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-119">Gets or sets the default owner group for all new folders and files created in the Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig EncryptionConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig EncryptionConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.EncryptionConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionConfig As UpdateEncryptionConfig" />
      <MemberSignature Language="F#" Value="member this.EncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.EncryptionConfig" />
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
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88a8d-120">ためのユーザーの回転角度を取得または設定は、Key Vault のキーを管理します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-120">Gets or sets used for rotation of user managed Key Vault keys.</span></span> <span data-ttu-id="88a8d-121">ユーザーが管理されている暗号化の Key Vault のキーを回転させるだけ使用できます。</span><span class="sxs-lookup"><span data-stu-id="88a8d-121">Can only be used to rotate a user managed encryption Key Vault key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.FirewallAllowAzureIps" />
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
            <span data-ttu-id="88a8d-122">取得または許可をファイアウォール経由の Azure 内で元の ip アドレスを許可するかの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-122">Gets or sets the current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span> <span data-ttu-id="88a8d-123">ファイアウォールが無効になっている場合は実行されていません。</span><span class="sxs-lookup"><span data-stu-id="88a8d-123">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="88a8d-124">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-124">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.FirewallState" />
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
            <span data-ttu-id="88a8d-125">取得またはこの Data Lake store アカウントの IP アドレスをファイアウォールの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-125">Gets or sets the current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="88a8d-126">ファイアウォールを無効にすると、既存のルールが削除されませんが、ファイアウォールが再び有効にするまで、無視だけ。</span><span class="sxs-lookup"><span data-stu-id="88a8d-126">Disabling the firewall does not remove existing rules, they will just be ignored until the firewall is re-enabled.</span></span> <span data-ttu-id="88a8d-127">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-127">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.NewTier" />
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
            <span data-ttu-id="88a8d-128">取得または次の月に使用するコミットメント層を設定します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-128">Gets or sets the commitment tier to use for next month.</span></span> <span data-ttu-id="88a8d-129">使用可能な値が含まれます: '消費'、'Commitment_1TB'、'Commitment_10TB'、'Commitment_100TB'、'Commitment_500TB'、'Commitment_1PB'、'Commitment_5PB'</span><span class="sxs-lookup"><span data-stu-id="88a8d-129">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88a8d-130">取得またはリソース タグを設定</span><span class="sxs-lookup"><span data-stu-id="88a8d-130">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedIdProviderState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.TrustedIdProviderState" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedIdProviderState As Nullable(Of TrustedIdProviderState)" />
      <MemberSignature Language="F#" Value="member this.TrustedIdProviderState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters.TrustedIdProviderState" />
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
            <span data-ttu-id="88a8d-131">取得またはこの Data Lake store アカウントの信頼された id プロバイダーの機能の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="88a8d-131">Gets or sets the current state of the trusted identity provider feature for this Data Lake store account.</span></span> <span data-ttu-id="88a8d-132">信頼できる id プロバイダーの機能を無効にすると、プロバイダーが削除されませんが、この機能を再び有効にするまで、無視だけ。</span><span class="sxs-lookup"><span data-stu-id="88a8d-132">Disabling trusted identity provider functionality does not remove the providers, they will just be ignored until this feature is re-enabled.</span></span> <span data-ttu-id="88a8d-133">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="88a8d-133">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>