<Type Name="StorageAccountCreateParameters" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4d56e-101">ストレージ アカウントを作成するときに使用されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4d56e-101">The parameters used when creating a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-102">StorageAccountCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-102">Initializes a new instance of the StorageAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters (Microsoft.Azure.Management.Storage.Models.Sku sku, Microsoft.Azure.Management.Storage.Models.Kind kind, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Models.Identity identity = null, Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Models.Encryption encryption = null, Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier = null, Nullable&lt;bool&gt; enableHttpsTrafficOnly = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Models.Sku sku, valuetype Microsoft.Azure.Management.Storage.Models.Kind kind, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Models.Identity identity, class Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Models.Encryption encryption, class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier, valuetype System.Nullable`1&lt;bool&gt; enableHttpsTrafficOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.#ctor(Microsoft.Azure.Management.Storage.Models.Sku,Microsoft.Azure.Management.Storage.Models.Kind,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Models.Identity,Microsoft.Azure.Management.Storage.Models.CustomDomain,Microsoft.Azure.Management.Storage.Models.Encryption,Microsoft.Azure.Management.Storage.Models.NetworkRuleSet,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccessTier},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters : Microsoft.Azure.Management.Storage.Models.Sku * Microsoft.Azure.Management.Storage.Models.Kind * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Models.Identity * Microsoft.Azure.Management.Storage.Models.CustomDomain * Microsoft.Azure.Management.Storage.Models.Encryption * Microsoft.Azure.Management.Storage.Models.NetworkRuleSet * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters (sku, kind, location, tags, identity, customDomain, encryption, networkRuleSet, accessTier, enableHttpsTrafficOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Models.Sku" />
        <Parameter Name="kind" Type="Microsoft.Azure.Management.Storage.Models.Kind" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Storage.Models.Identity" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Models.Encryption" />
        <Parameter Name="networkRuleSet" Type="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" />
        <Parameter Name="enableHttpsTrafficOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sku"><span data-ttu-id="4d56e-103">必須。</span><span class="sxs-lookup"><span data-stu-id="4d56e-103">Required.</span></span> <span data-ttu-id="4d56e-104">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-104">Gets or sets the sku name.</span></span></param>
        <param name="kind"><span data-ttu-id="4d56e-105">必須。</span><span class="sxs-lookup"><span data-stu-id="4d56e-105">Required.</span></span> <span data-ttu-id="4d56e-106">ストレージ アカウントの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-106">Indicates the type of storage account.</span></span>
            <span data-ttu-id="4d56e-107">使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'</span><span class="sxs-lookup"><span data-stu-id="4d56e-107">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span></param>
        <param name="location"><span data-ttu-id="4d56e-108">必須。</span><span class="sxs-lookup"><span data-stu-id="4d56e-108">Required.</span></span> <span data-ttu-id="4d56e-109">取得またはリソースの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-109">Gets or sets the location of the resource.</span></span> <span data-ttu-id="4d56e-110">これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-110">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="4d56e-111">その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。</span><span class="sxs-lookup"><span data-stu-id="4d56e-111">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span></param>
        <param name="tags"><span data-ttu-id="4d56e-112">取得またはリソースを説明するキー値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-112">Gets or sets a list of key value pairs that describe the resource.</span></span> <span data-ttu-id="4d56e-113">これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。</span><span class="sxs-lookup"><span data-stu-id="4d56e-113">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="4d56e-114">リソースの最大で 15 個のタグを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="4d56e-114">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="4d56e-115">各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-115">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span></param>
        <param name="identity"><span data-ttu-id="4d56e-116">リソースの id。</span><span class="sxs-lookup"><span data-stu-id="4d56e-116">The identity of the resource.</span></span></param>
        <param name="customDomain"><span data-ttu-id="4d56e-117">ストレージ アカウントに割り当てられているユーザーのドメイン。</span><span class="sxs-lookup"><span data-stu-id="4d56e-117">User domain assigned to the storage account.</span></span> <span data-ttu-id="4d56e-118">名前は、CNAME ソースです。</span><span class="sxs-lookup"><span data-stu-id="4d56e-118">Name is the CNAME source.</span></span> <span data-ttu-id="4d56e-119">1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。</span><span class="sxs-lookup"><span data-stu-id="4d56e-119">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="4d56e-120">既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-120">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span></param>
        <param name="encryption"><span data-ttu-id="4d56e-121">アカウントの暗号化の設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-121">Provides the encryption settings on the account.</span></span> <span data-ttu-id="4d56e-122">アカウントの暗号化設定は変わりません指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="4d56e-122">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="4d56e-123">既定の設定は暗号化されません。</span><span class="sxs-lookup"><span data-stu-id="4d56e-123">The default setting is unencrypted.</span></span></param>
        <param name="networkRuleSet"><span data-ttu-id="4d56e-124">ネットワーク ルール セット</span><span class="sxs-lookup"><span data-stu-id="4d56e-124">Network rule set</span></span></param>
        <param name="accessTier"><span data-ttu-id="4d56e-125">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-125">Required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="4d56e-126">アクセス層は、課金のために使用します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-126">The access tier used for billing.</span></span> <span data-ttu-id="4d56e-127">使用可能な値が含まれます: 'ホット'、'ね'</span><span class="sxs-lookup"><span data-stu-id="4d56e-127">Possible values include: 'Hot', 'Cool'</span></span></param>
        <param name="enableHttpsTrafficOnly"><span data-ttu-id="4d56e-128">場合にのみストレージ サービスへの https トラフィックを許可を true に設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-128">Allows https traffic only to storage service if sets to true.</span></span></param>
        <summary>
            <span data-ttu-id="4d56e-129">StorageAccountCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-129">Initializes a new instance of the StorageAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-130">ストレージ アカウントの種類が必要な設定を取得または BlobStorage を = です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-130">Gets or sets required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="4d56e-131">アクセス層は、課金のために使用します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-131">The access tier used for billing.</span></span> <span data-ttu-id="4d56e-132">使用可能な値が含まれます: 'ホット'、'ね'</span><span class="sxs-lookup"><span data-stu-id="4d56e-132">Possible values include: 'Hot', 'Cool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-133">取得またはストレージ アカウントに割り当てられたユーザー ドメインを設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-133">Gets or sets user domain assigned to the storage account.</span></span> <span data-ttu-id="4d56e-134">名前は、CNAME ソースです。</span><span class="sxs-lookup"><span data-stu-id="4d56e-134">Name is the CNAME source.</span></span> <span data-ttu-id="4d56e-135">1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。</span><span class="sxs-lookup"><span data-stu-id="4d56e-135">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="4d56e-136">既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-136">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttpsTrafficOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttpsTrafficOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttpsTrafficOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.EnableHttpsTrafficOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttpsTrafficOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttpsTrafficOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.EnableHttpsTrafficOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsHttpsTrafficOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-137">場合に記憶域サービスのみ https トラフィックを許可するを取得または設定を true に設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-137">Gets or sets allows https traffic only to storage service if sets to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-138">取得または設定は、アカウントの暗号化設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-138">Gets or sets provides the encryption settings on the account.</span></span> <span data-ttu-id="4d56e-139">アカウントの暗号化設定は変わりません指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="4d56e-139">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="4d56e-140">既定の設定は暗号化されません。</span><span class="sxs-lookup"><span data-stu-id="4d56e-140">The default setting is unencrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Storage.Models.Identity with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-141">取得またはリソースの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-141">Gets or sets the identity of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Kind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Models.Kind with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-142">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-142">Gets or sets required.</span></span> <span data-ttu-id="4d56e-143">ストレージ アカウントの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-143">Indicates the type of storage account.</span></span>
            <span data-ttu-id="4d56e-144">使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'</span><span class="sxs-lookup"><span data-stu-id="4d56e-144">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-145">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-145">Gets or sets required.</span></span> <span data-ttu-id="4d56e-146">取得またはリソースの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-146">Gets or sets the location of the resource.</span></span>
            <span data-ttu-id="4d56e-147">これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-147">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="4d56e-148">その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。</span><span class="sxs-lookup"><span data-stu-id="4d56e-148">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkRuleSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.NetworkRuleSet" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkRuleSet As NetworkRuleSet" />
      <MemberSignature Language="F#" Value="member this.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.NetworkRuleSet with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.NetworkRuleSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAcls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.NetworkRuleSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-149">ルール セットのネットワーク取得または設定</span><span class="sxs-lookup"><span data-stu-id="4d56e-149">Gets or sets network rule set</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-150">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-150">Gets or sets required.</span></span> <span data-ttu-id="4d56e-151">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-151">Gets or sets the sku name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4d56e-152">取得またはリソースを説明するキー値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-152">Gets or sets a list of key value pairs that describe the resource.</span></span>
            <span data-ttu-id="4d56e-153">これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。</span><span class="sxs-lookup"><span data-stu-id="4d56e-153">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="4d56e-154">リソースの最大で 15 個のタグを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="4d56e-154">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="4d56e-155">各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。</span><span class="sxs-lookup"><span data-stu-id="4d56e-155">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d56e-156">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4d56e-156">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d56e-157">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d56e-157">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>