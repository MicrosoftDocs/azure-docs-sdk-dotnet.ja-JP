<Type Name="Certificate" FullName="Microsoft.Azure.Management.WebSites.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="602a1-101">アプリの SSL 証明書。</span><span class="sxs-lookup"><span data-stu-id="602a1-101">SSL certificate for an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Certificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="602a1-102">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="602a1-102">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string friendlyName = null, string subjectName = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, byte[] pfxBlob = null, string siteName = null, string selfLink = null, string issuer = null, Nullable&lt;DateTime&gt; issueDate = null, Nullable&lt;DateTime&gt; expirationDate = null, string password = null, string thumbprint = null, Nullable&lt;bool&gt; valid = null, byte[] cerBlob = null, string publicKeyHash = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; keyVaultSecretStatus = null, string geoRegion = null, string serverFarmId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string friendlyName, string subjectName, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, unsigned int8[] pfxBlob, string siteName, string selfLink, string issuer, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; issueDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationDate, string password, string thumbprint, valuetype System.Nullable`1&lt;bool&gt; valid, unsigned int8[] cerBlob, string publicKeyHash, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; keyVaultSecretStatus, string geoRegion, string serverFarmId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Certificate.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Byte[],System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},System.Byte[],System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus},System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Certificate : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * byte[] * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * byte[] * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Certificate" Usage="new Microsoft.Azure.Management.WebSites.Models.Certificate (location, id, name, kind, type, tags, friendlyName, subjectName, hostNames, pfxBlob, siteName, selfLink, issuer, issueDate, expirationDate, password, thumbprint, valid, cerBlob, publicKeyHash, hostingEnvironmentProfile, keyVaultId, keyVaultSecretName, keyVaultSecretStatus, geoRegion, serverFarmId)" />
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
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="subjectName" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="pfxBlob" Type="System.Byte[]" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="selfLink" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issueDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="valid" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cerBlob" Type="System.Byte[]" />
        <Parameter Name="publicKeyHash" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="keyVaultSecretStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" />
        <Parameter Name="geoRegion" Type="System.String" />
        <Parameter Name="serverFarmId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="602a1-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="602a1-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="602a1-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="602a1-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="602a1-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="602a1-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="602a1-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="602a1-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="602a1-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="602a1-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="602a1-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="602a1-108">Resource tags.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="602a1-109">証明書のフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="602a1-109">Friendly name of the certificate.</span></span></param>
        <param name="subjectName"><span data-ttu-id="602a1-110">証明書のサブジェクト名。</span><span class="sxs-lookup"><span data-stu-id="602a1-110">Subject name of the certificate.</span></span></param>
        <param name="hostNames"><span data-ttu-id="602a1-111">ホスト名に、証明書が適用されます。</span><span class="sxs-lookup"><span data-stu-id="602a1-111">Host names the certificate applies to.</span></span></param>
        <param name="pfxBlob"><span data-ttu-id="602a1-112">Pfx blob。</span><span class="sxs-lookup"><span data-stu-id="602a1-112">Pfx blob.</span></span></param>
        <param name="siteName"><span data-ttu-id="602a1-113">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="602a1-113">App name.</span></span></param>
        <param name="selfLink"><span data-ttu-id="602a1-114">自己リンク。</span><span class="sxs-lookup"><span data-stu-id="602a1-114">Self link.</span></span></param>
        <param name="issuer"><span data-ttu-id="602a1-115">証明書の発行者。</span><span class="sxs-lookup"><span data-stu-id="602a1-115">Certificate issuer.</span></span></param>
        <param name="issueDate"><span data-ttu-id="602a1-116">証明書の問題の日付。</span><span class="sxs-lookup"><span data-stu-id="602a1-116">Certificate issue Date.</span></span></param>
        <param name="expirationDate"><span data-ttu-id="602a1-117">証明書 expriration 日付です。</span><span class="sxs-lookup"><span data-stu-id="602a1-117">Certificate expriration date.</span></span></param>
        <param name="password"><span data-ttu-id="602a1-118">証明書のパスワード。</span><span class="sxs-lookup"><span data-stu-id="602a1-118">Certificate password.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="602a1-119">証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="602a1-119">Certificate thumbprint.</span></span></param>
        <param name="valid"><span data-ttu-id="602a1-120">証明書は有効ですか?</span><span class="sxs-lookup"><span data-stu-id="602a1-120">Is the certificate valid?.</span></span></param>
        <param name="cerBlob"><span data-ttu-id="602a1-121">.Cer ファイルの実際のバイト数</span><span class="sxs-lookup"><span data-stu-id="602a1-121">Raw bytes of .cer file</span></span></param>
        <param name="publicKeyHash"><span data-ttu-id="602a1-122">公開キー ハッシュします。</span><span class="sxs-lookup"><span data-stu-id="602a1-122">Public key hash.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="602a1-123">証明書の使用を App Service 環境を指定します。</span><span class="sxs-lookup"><span data-stu-id="602a1-123">Specification for the App Service Environment to use for the certificate.</span></span></param>
        <param name="keyVaultId"><span data-ttu-id="602a1-124">Key Vault Csm リソース id。</span><span class="sxs-lookup"><span data-stu-id="602a1-124">Key Vault Csm resource Id.</span></span></param>
        <param name="keyVaultSecretName"><span data-ttu-id="602a1-125">Key Vault シークレットの名前です。</span><span class="sxs-lookup"><span data-stu-id="602a1-125">Key Vault secret name.</span></span></param>
        <param name="keyVaultSecretStatus"><span data-ttu-id="602a1-126">Key Vault シークレットの状態です。</span><span class="sxs-lookup"><span data-stu-id="602a1-126">Status of the Key Vault secret.</span></span>
            <span data-ttu-id="602a1-127">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="602a1-127">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span></param>
        <param name="geoRegion"><span data-ttu-id="602a1-128">証明書の領域。</span><span class="sxs-lookup"><span data-stu-id="602a1-128">Region of the certificate.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="602a1-129">リソース ID、関連付けられている App Service プランの設定として書式設定:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="602a1-129">Resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span></param>
        <summary>
            <span data-ttu-id="602a1-130">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="602a1-130">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CerBlob">
      <MemberSignature Language="C#" Value="public byte[] CerBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] CerBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.CerBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CerBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.CerBlob : byte[]" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.CerBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cerBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-131">.Cer ファイルの生のバイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-131">Gets raw bytes of .cer file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.ExpirationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.ExpirationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-132">Expriration 日付の証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-132">Gets certificate expriration date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-133">証明書のフレンドリ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-133">Gets friendly name of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegion">
      <MemberSignature Language="C#" Value="public string GeoRegion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.GeoRegion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegion As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegion : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.GeoRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-134">証明書の領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-134">Gets region of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.HostingEnvironmentProfile" />
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
            <span data-ttu-id="602a1-135">証明書の使用を App Service 環境の仕様を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-135">Gets specification for the App Service Environment to use for the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.HostNames" />
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
            <span data-ttu-id="602a1-136">取得または証明書が対象のホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="602a1-136">Gets or sets host names the certificate applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssueDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IssueDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IssueDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.IssueDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssueDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IssueDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.IssueDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.issueDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-137">証明書の発行日を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-137">Gets certificate issue Date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-138">発行者の証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-138">Gets certificate issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-139">取得または設定キーの資格情報コンテナー Csm リソース id。</span><span class="sxs-lookup"><span data-stu-id="602a1-139">Gets or sets key Vault Csm resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-140">取得またはキーの資格情報コンテナーのシークレット名を設定します。</span><span class="sxs-lookup"><span data-stu-id="602a1-140">Gets or sets key Vault secret name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; KeyVaultSecretStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; KeyVaultSecretStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultSecretStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultSecretStatus As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretStatus : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.KeyVaultSecretStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-141">秘密キー コンテナーの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-141">Gets status of the Key Vault secret.</span></span> <span data-ttu-id="602a1-142">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="602a1-142">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-143">取得または証明書のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="602a1-143">Gets or sets certificate password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PfxBlob">
      <MemberSignature Language="C#" Value="public byte[] PfxBlob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] PfxBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.PfxBlob" />
      <MemberSignature Language="VB.NET" Value="Public Property PfxBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.PfxBlob : byte[] with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.PfxBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pfxBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-144">取得または pfx blob を設定します。</span><span class="sxs-lookup"><span data-stu-id="602a1-144">Gets or sets pfx blob.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeyHash">
      <MemberSignature Language="C#" Value="public string PublicKeyHash { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicKeyHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.PublicKeyHash" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicKeyHash As String" />
      <MemberSignature Language="F#" Value="member this.PublicKeyHash : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.PublicKeyHash" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicKeyHash")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-145">公開キー ハッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-145">Gets public key hash.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.SelfLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.selfLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-146">自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-146">Gets self link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.ServerFarmId" />
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
            <span data-ttu-id="602a1-147">取得または設定として書式設定、関連付けられている、App Service プランのリソース ID:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</span><span class="sxs-lookup"><span data-stu-id="602a1-147">Gets or sets resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-148">アプリ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-148">Gets app name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectName">
      <MemberSignature Language="C#" Value="public string SubjectName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.SubjectName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubjectName As String" />
      <MemberSignature Language="F#" Value="member this.SubjectName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.SubjectName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subjectName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-149">証明書のサブジェクト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-149">Gets subject name of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-150">証明書の拇印を取得します。</span><span class="sxs-lookup"><span data-stu-id="602a1-150">Gets certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Valid">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Valid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Valid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Certificate.Valid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Valid As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Valid : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Certificate.Valid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.valid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="602a1-151">取得は、有効な証明書ですか?</span><span class="sxs-lookup"><span data-stu-id="602a1-151">Gets is the certificate valid?.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Certificate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="certificate.Validate " />
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
            <span data-ttu-id="602a1-152">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="602a1-152">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="602a1-153">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="602a1-153">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>