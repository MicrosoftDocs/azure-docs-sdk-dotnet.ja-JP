<Type Name="Domain" FullName="Microsoft.Azure.Management.WebSites.Models.Domain">
  <TypeSignature Language="C#" Value="public class Domain : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Domain extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Domain" />
  <TypeSignature Language="VB.NET" Value="Public Class Domain&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Domain = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="e4c34-101">ドメインに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-101">Information about a domain.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Domain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Domain.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-102">ドメイン クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-102">Initializes a new instance of the Domain class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Domain (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.WebSites.Models.Contact contactAdmin = null, Microsoft.Azure.Management.WebSites.Models.Contact contactBilling = null, Microsoft.Azure.Management.WebSites.Models.Contact contactRegistrant = null, Microsoft.Azure.Management.WebSites.Models.Contact contactTech = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; registrationStatus = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null, Nullable&lt;bool&gt; privacy = null, Nullable&lt;DateTime&gt; createdTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;DateTime&gt; lastRenewedTime = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;bool&gt; readyForDnsRecordManagement = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; managedHostNames = null, Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent consent = null, System.Collections.Generic.IList&lt;string&gt; domainNotRenewableReasons = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; dnsType = null, string dnsZoneId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; targetDnsType = null, string authCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.WebSites.Models.Contact contactAdmin, class Microsoft.Azure.Management.WebSites.Models.Contact contactBilling, class Microsoft.Azure.Management.WebSites.Models.Contact contactRegistrant, class Microsoft.Azure.Management.WebSites.Models.Contact contactTech, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; registrationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, class System.Collections.Generic.IList`1&lt;string&gt; nameServers, valuetype System.Nullable`1&lt;bool&gt; privacy, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRenewedTime, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;bool&gt; readyForDnsRecordManagement, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostName&gt; managedHostNames, class Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent consent, class System.Collections.Generic.IList`1&lt;string&gt; domainNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; dnsType, string dnsZoneId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; targetDnsType, string authCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Domain.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,System.Nullable{Microsoft.Azure.Management.WebSites.Models.DomainStatus},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HostName},Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.DnsType},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.DnsType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional contactAdmin As Contact = null, Optional contactBilling As Contact = null, Optional contactRegistrant As Contact = null, Optional contactTech As Contact = null, Optional registrationStatus As Nullable(Of DomainStatus) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional nameServers As IList(Of String) = null, Optional privacy As Nullable(Of Boolean) = null, Optional createdTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional lastRenewedTime As Nullable(Of DateTime) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional readyForDnsRecordManagement As Nullable(Of Boolean) = null, Optional managedHostNames As IList(Of HostName) = null, Optional consent As DomainPurchaseConsent = null, Optional domainNotRenewableReasons As IList(Of String) = null, Optional dnsType As Nullable(Of DnsType) = null, Optional dnsZoneId As String = null, Optional targetDnsType As Nullable(Of DnsType) = null, Optional authCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Domain : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; * Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="new Microsoft.Azure.Management.WebSites.Models.Domain (location, id, name, kind, type, tags, contactAdmin, contactBilling, contactRegistrant, contactTech, registrationStatus, provisioningState, nameServers, privacy, createdTime, expirationTime, lastRenewedTime, autoRenew, readyForDnsRecordManagement, managedHostNames, consent, domainNotRenewableReasons, dnsType, dnsZoneId, targetDnsType, authCode)" />
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
        <Parameter Name="contactAdmin" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactBilling" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactRegistrant" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactTech" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="registrationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="privacy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastRenewedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="readyForDnsRecordManagement" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="managedHostNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;" />
        <Parameter Name="consent" Type="Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent" />
        <Parameter Name="domainNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="dnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;" />
        <Parameter Name="dnsZoneId" Type="System.String" />
        <Parameter Name="targetDnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;" />
        <Parameter Name="authCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="e4c34-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="e4c34-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="e4c34-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="e4c34-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="e4c34-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e4c34-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="e4c34-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e4c34-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="e4c34-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="e4c34-108">Resource tags.</span></span></param>
        <param name="contactAdmin"><span data-ttu-id="e4c34-109">管理者に問い合わせてください。</span><span class="sxs-lookup"><span data-stu-id="e4c34-109">Administrative contact.</span></span></param>
        <param name="contactBilling"><span data-ttu-id="e4c34-110">課金サービスにお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="e4c34-110">Billing contact.</span></span></param>
        <param name="contactRegistrant"><span data-ttu-id="e4c34-111">登録者にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="e4c34-111">Registrant contact.</span></span></param>
        <param name="contactTech"><span data-ttu-id="e4c34-112">技術的に問い合わせてください。</span><span class="sxs-lookup"><span data-stu-id="e4c34-112">Technical contact.</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="e4c34-113">ドメインの登録状態です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-113">Domain registration status.</span></span>
            <span data-ttu-id="e4c34-114">使用可能な値が含まれます: 'アクティブ'、'待機中'、'キャンセル'、'Confiscated'、'Disabled'、'除外'、'有効期限が切れて'、'失敗'、'保持されている'、'ロック'、'保留中'、'Reserved'、'元に戻された'、'中断'、'転送'、'Unknown'、'ロックされていない'、'Unparked'、' Parked'、'更新 '、'JsonConverterFailed'</span><span class="sxs-lookup"><span data-stu-id="e4c34-114">Possible values include: 'Active', 'Awaiting', 'Cancelled', 'Confiscated', 'Disabled', 'Excluded', 'Expired', 'Failed', 'Held', 'Locked', 'Parked', 'Pending', 'Reserved', 'Reverted', 'Suspended', 'Transferred', 'Unknown', 'Unlocked', 'Unparked', 'Updated', 'JsonConverterFailed'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="e4c34-115">ドメインのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="e4c34-115">Domain provisioning state.</span></span> <span data-ttu-id="e4c34-116">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="e4c34-116">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <param name="nameServers"><span data-ttu-id="e4c34-117">サーバーの名前を付けます。</span><span class="sxs-lookup"><span data-stu-id="e4c34-117">Name servers.</span></span></param>
        <param name="privacy"><span data-ttu-id="e4c34-118">&lt;コード&gt;true&lt;/code&gt;ドメイン プライバシーがこのドメインに対応している、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-118">&lt;code&gt;true&lt;/code&gt; if domain privacy is enabled for this domain; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="createdTime"><span data-ttu-id="e4c34-119">ドメインの作成のタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="e4c34-119">Domain creation timestamp.</span></span></param>
        <param name="expirationTime"><span data-ttu-id="e4c34-120">ドメインの有効期限タイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="e4c34-120">Domain expiration timestamp.</span></span></param>
        <param name="lastRenewedTime"><span data-ttu-id="e4c34-121">ドメインの最後の時間が書き換えられたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="e4c34-121">Timestamp when the domain was renewed last time.</span></span></param>
        <param name="autoRenew"><span data-ttu-id="e4c34-122">&lt;コード&gt;true&lt;/code&gt;場合は、ドメインが自動的に更新された、それ以外にする必要があります&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-122">&lt;code&gt;true&lt;/code&gt; if the domain should be automatically renewed; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="readyForDnsRecordManagement"><span data-ttu-id="e4c34-123">&lt;コード&gt;true&lt;/code&gt; Azure App Service アプリをこのドメインを割り当てることができる場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e4c34-123">&lt;code&gt;true&lt;/code&gt; if Azure can assign this domain to App Service apps; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="e4c34-124">この値はある&lt;コード&gt;true&lt;/code&gt;ドメイン登録ステータスがアクティブで、Azure へのプログラムによるアクセスでは、名前のサーバーでホストされている場合。</span><span class="sxs-lookup"><span data-stu-id="e4c34-124">This value will be &lt;code&gt;true&lt;/code&gt; if domain registration status is active and it is hosted on name servers Azure has programmatic access to.</span></span></param>
        <param name="managedHostNames"><span data-ttu-id="e4c34-125">すべてのホスト名は、ドメインから派生し、Azure リソースに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="e4c34-125">All hostnames derived from the domain and assigned to Azure resources.</span></span></param>
        <param name="consent"><span data-ttu-id="e4c34-126">法的契約同意します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-126">Legal agreement consent.</span></span></param>
        <param name="domainNotRenewableReasons"><span data-ttu-id="e4c34-127">ドメインが更新可能な理由上の理由からです。</span><span class="sxs-lookup"><span data-stu-id="e4c34-127">Reasons why domain is not renewable.</span></span></param>
        <param name="dnsType"><span data-ttu-id="e4c34-128">現在の DNS を入力します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-128">Current DNS type.</span></span> <span data-ttu-id="e4c34-129">使用可能な値が含まれます: 'AzureDns'、'DefaultDomainRegistrarDns'</span><span class="sxs-lookup"><span data-stu-id="e4c34-129">Possible values include: 'AzureDns', 'DefaultDomainRegistrarDns'</span></span></param>
        <param name="dnsZoneId"><span data-ttu-id="e4c34-130">Azure DNS ゾーンを使用するには</span><span class="sxs-lookup"><span data-stu-id="e4c34-130">Azure DNS Zone to use</span></span></param>
        <param name="targetDnsType"><span data-ttu-id="e4c34-131">ターゲット DNS の種類 (使用される移行)。</span><span class="sxs-lookup"><span data-stu-id="e4c34-131">Target DNS type (would be used for migration).</span></span> <span data-ttu-id="e4c34-132">使用可能な値が含まれます: 'AzureDns'、'DefaultDomainRegistrarDns'</span><span class="sxs-lookup"><span data-stu-id="e4c34-132">Possible values include: 'AzureDns', 'DefaultDomainRegistrarDns'</span></span></param>
        <param name="authCode">To be added.</param>
        <summary>
            <span data-ttu-id="e4c34-133">ドメイン クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-133">Initializes a new instance of the Domain class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthCode">
      <MemberSignature Language="C#" Value="public string AuthCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.AuthCode" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthCode As String" />
      <MemberSignature Language="F#" Value="member this.AuthCode : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.AuthCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-134">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 自動的に更新された、それ以外のドメインがある場合&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="e4c34-134">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the domain should be automatically renewed; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Consent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent Consent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent Consent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.Consent" />
      <MemberSignature Language="VB.NET" Value="Public Property Consent As DomainPurchaseConsent" />
      <MemberSignature Language="F#" Value="member this.Consent : Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.Consent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-135">取得または法的な契約同意を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-135">Gets or sets legal agreement consent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactAdmin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ContactAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactAdmin As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactAdmin : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ContactAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-136">取得または管理者の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-136">Gets or sets administrative contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactBilling">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactBilling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactBilling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ContactBilling" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactBilling As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactBilling : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ContactBilling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactBilling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-137">取得または設定の課金にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="e4c34-137">Gets or sets billing contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactRegistrant">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactRegistrant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactRegistrant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ContactRegistrant" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactRegistrant As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactRegistrant : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ContactRegistrant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactRegistrant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-138">取得または登録者の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-138">Gets or sets registrant contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactTech">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactTech { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactTech" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ContactTech" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactTech As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactTech : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ContactTech" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactTech")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-139">取得または技術担当者を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-139">Gets or sets technical contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-140">ドメインの作成のタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-140">Gets domain creation timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; DnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; DnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.DnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.DnsType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.DnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-141">取得または DNS の現在の型を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-141">Gets or sets current DNS type.</span></span> <span data-ttu-id="e4c34-142">使用可能な値が含まれます: 'AzureDns'、'DefaultDomainRegistrarDns'</span><span class="sxs-lookup"><span data-stu-id="e4c34-142">Possible values include: 'AzureDns', 'DefaultDomainRegistrarDns'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsZoneId">
      <MemberSignature Language="C#" Value="public string DnsZoneId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsZoneId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.DnsZoneId" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsZoneId As String" />
      <MemberSignature Language="F#" Value="member this.DnsZoneId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.DnsZoneId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsZoneId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-143">取得または設定を使用する azure の DNS ゾーン</span><span class="sxs-lookup"><span data-stu-id="e4c34-143">Gets or sets azure DNS Zone to use</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DomainNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DomainNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.DomainNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DomainNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.DomainNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-144">ドメインが更新可能な理由の理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-144">Gets reasons why domain is not renewable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-145">ドメインの有効期限タイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-145">Gets domain expiration timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRenewedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRenewedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRenewedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.LastRenewedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRenewedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRenewedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.LastRenewedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastRenewedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-146">ドメインの最後の時間が書き換えられたときは、タイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-146">Gets timestamp when the domain was renewed last time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; ManagedHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostName&gt; ManagedHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ManagedHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedHostNames As IList(Of HostName)" />
      <MemberSignature Language="F#" Value="member this.ManagedHostNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ManagedHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managedHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-147">ドメインから派生し、Azure リソースに割り当てられているすべてのホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-147">Gets all hostnames derived from the domain and assigned to Azure resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nameServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-148">サーバーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-148">Gets name servers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Privacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public Property Privacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Privacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.Privacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-149">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; ドメインのプライバシーはこのドメインに対応している、それ以外の場合&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="e4c34-149">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if domain privacy is enabled for this domain; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ProvisioningState" />
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
            <span data-ttu-id="e4c34-150">プロビジョニング状態をドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-150">Gets domain provisioning state.</span></span> <span data-ttu-id="e4c34-151">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="e4c34-151">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadyForDnsRecordManagement">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReadyForDnsRecordManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReadyForDnsRecordManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.ReadyForDnsRecordManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadyForDnsRecordManagement As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReadyForDnsRecordManagement : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.ReadyForDnsRecordManagement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readyForDnsRecordManagement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-152">取得&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; Azure App Service アプリをこのドメインを割り当てることができます場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="e4c34-152">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Azure can assign this domain to App Service apps; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="e4c34-153">この値になります&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; ドメインの登録状態がアクティブで、Azure へのプログラムによるアクセスでは、名前のサーバーでホストされている場合。</span><span class="sxs-lookup"><span data-stu-id="e4c34-153">This value will be &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if domain registration status is active and it is hosted on name servers Azure has programmatic access to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; RegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationStatus As Nullable(Of DomainStatus)" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-154">ドメインの登録状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-154">Gets domain registration status.</span></span> <span data-ttu-id="e4c34-155">使用可能な値が含まれます: 'アクティブ'、'待機中'、'キャンセル'、'Confiscated'、'Disabled'、'除外'、'有効期限が切れて'、'失敗'、'保持されている'、'ロック'、'保留中'、'Reserved'、'元に戻された'、'中断'、'転送'、'Unknown'、'ロックされていない'、'Unparked'、' Parked'、'更新 '、'JsonConverterFailed'</span><span class="sxs-lookup"><span data-stu-id="e4c34-155">Possible values include: 'Active', 'Awaiting', 'Cancelled', 'Confiscated', 'Disabled', 'Excluded', 'Expired', 'Failed', 'Held', 'Locked', 'Parked', 'Pending', 'Reserved', 'Reverted', 'Suspended', 'Transferred', 'Unknown', 'Unlocked', 'Unparked', 'Updated', 'JsonConverterFailed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; TargetDnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; TargetDnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Domain.TargetDnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.TargetDnsType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Domain.TargetDnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetDnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4c34-156">取得またはターゲット DNS の種類 (使用される移行) を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-156">Gets or sets target DNS type (would be used for migration).</span></span>
            <span data-ttu-id="e4c34-157">使用可能な値が含まれます: 'AzureDns'、'DefaultDomainRegistrarDns'</span><span class="sxs-lookup"><span data-stu-id="e4c34-157">Possible values include: 'AzureDns', 'DefaultDomainRegistrarDns'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Domain.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="domain.Validate " />
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
            <span data-ttu-id="e4c34-158">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e4c34-158">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e4c34-159">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e4c34-159">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>