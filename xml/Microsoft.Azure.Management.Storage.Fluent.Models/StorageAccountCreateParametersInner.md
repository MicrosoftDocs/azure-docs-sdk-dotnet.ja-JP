<Type Name="StorageAccountCreateParametersInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParametersInner" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6965b-101">ストレージ アカウントを作成するときに使用されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="6965b-101">The parameters used when creating a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6965b-102">StorageAccountCreateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6965b-102">Initializes a new instance of the StorageAccountCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner (Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.Sku,Microsoft.Azure.Management.Storage.Fluent.Models.Kind,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner : Microsoft.Azure.Management.Storage.Fluent.Models.Sku * Microsoft.Azure.Management.Storage.Fluent.Models.Kind * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner (sku, kind, location, tags, customDomain, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="kind" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Kind" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="sku"><span data-ttu-id="6965b-103">必須。</span><span class="sxs-lookup"><span data-stu-id="6965b-103">Required.</span></span> <span data-ttu-id="6965b-104">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-104">Gets or sets the sku name.</span></span></param>
        <param name="kind"><span data-ttu-id="6965b-105">必須。</span><span class="sxs-lookup"><span data-stu-id="6965b-105">Required.</span></span> <span data-ttu-id="6965b-106">ストレージ アカウントの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="6965b-106">Indicates the type of storage account.</span></span>
            <span data-ttu-id="6965b-107">使用可能な値が含まれます: 'Storage'、'BlobStorage'</span><span class="sxs-lookup"><span data-stu-id="6965b-107">Possible values include: 'Storage', 'BlobStorage'</span></span></param>
        <param name="location"><span data-ttu-id="6965b-108">必須。</span><span class="sxs-lookup"><span data-stu-id="6965b-108">Required.</span></span> <span data-ttu-id="6965b-109">取得またはリソースの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-109">Gets or sets the location of the resource.</span></span> <span data-ttu-id="6965b-110">これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。</span><span class="sxs-lookup"><span data-stu-id="6965b-110">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="6965b-111">その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。</span><span class="sxs-lookup"><span data-stu-id="6965b-111">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span></param>
        <param name="tags"><span data-ttu-id="6965b-112">取得またはリソースを説明するキー値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-112">Gets or sets a list of key value pairs that describe the resource.</span></span> <span data-ttu-id="6965b-113">これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。</span><span class="sxs-lookup"><span data-stu-id="6965b-113">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="6965b-114">リソースの最大で 15 個のタグを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="6965b-114">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="6965b-115">各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。</span><span class="sxs-lookup"><span data-stu-id="6965b-115">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span></param>
        <param name="customDomain"><span data-ttu-id="6965b-116">ストレージ アカウントに割り当てられているユーザーのドメイン。</span><span class="sxs-lookup"><span data-stu-id="6965b-116">User domain assigned to the storage account.</span></span> <span data-ttu-id="6965b-117">名前は、CNAME ソースです。</span><span class="sxs-lookup"><span data-stu-id="6965b-117">Name is the CNAME source.</span></span> <span data-ttu-id="6965b-118">1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。</span><span class="sxs-lookup"><span data-stu-id="6965b-118">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="6965b-119">既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="6965b-119">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span></param>
        <param name="encryption"><span data-ttu-id="6965b-120">アカウントの暗号化の設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="6965b-120">Provides the encryption settings on the account.</span></span> <span data-ttu-id="6965b-121">アカウントの暗号化設定は変わりません指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="6965b-121">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="6965b-122">既定の設定は暗号化されません。</span><span class="sxs-lookup"><span data-stu-id="6965b-122">The default setting is unencrypted.</span></span></param>
        <param name="accessTier"><span data-ttu-id="6965b-123">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。</span><span class="sxs-lookup"><span data-stu-id="6965b-123">Required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="6965b-124">アクセス層は、課金のために使用します。</span><span class="sxs-lookup"><span data-stu-id="6965b-124">The access tier used for billing.</span></span> <span data-ttu-id="6965b-125">使用可能な値が含まれます: 'ホット'、'ね'</span><span class="sxs-lookup"><span data-stu-id="6965b-125">Possible values include: 'Hot', 'Cool'</span></span></param>
        <summary>
            <span data-ttu-id="6965b-126">StorageAccountCreateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6965b-126">Initializes a new instance of the StorageAccountCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6965b-127">ストレージ アカウントの種類が必要な設定を取得または BlobStorage を = です。</span><span class="sxs-lookup"><span data-stu-id="6965b-127">Gets or sets required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="6965b-128">アクセス層は、課金のために使用します。</span><span class="sxs-lookup"><span data-stu-id="6965b-128">The access tier used for billing.</span></span> <span data-ttu-id="6965b-129">使用可能な値が含まれます: 'ホット'、'ね'</span><span class="sxs-lookup"><span data-stu-id="6965b-129">Possible values include: 'Hot', 'Cool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6965b-130">取得またはストレージ アカウントに割り当てられたユーザー ドメインを設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-130">Gets or sets user domain assigned to the storage account.</span></span> <span data-ttu-id="6965b-131">名前は、CNAME ソースです。</span><span class="sxs-lookup"><span data-stu-id="6965b-131">Name is the CNAME source.</span></span> <span data-ttu-id="6965b-132">1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。</span><span class="sxs-lookup"><span data-stu-id="6965b-132">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="6965b-133">既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="6965b-133">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6965b-134">取得または設定は、アカウントの暗号化設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="6965b-134">Gets or sets provides the encryption settings on the account.</span></span> <span data-ttu-id="6965b-135">アカウントの暗号化設定は変わりません指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="6965b-135">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="6965b-136">既定の設定は暗号化されません。</span><span class="sxs-lookup"><span data-stu-id="6965b-136">The default setting is unencrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Fluent.Models.Kind with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6965b-137">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="6965b-137">Gets or sets required.</span></span> <span data-ttu-id="6965b-138">ストレージ アカウントの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="6965b-138">Indicates the type of storage account.</span></span>
            <span data-ttu-id="6965b-139">使用可能な値が含まれます: 'Storage'、'BlobStorage'</span><span class="sxs-lookup"><span data-stu-id="6965b-139">Possible values include: 'Storage', 'BlobStorage'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6965b-140">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="6965b-140">Gets or sets required.</span></span> <span data-ttu-id="6965b-141">取得またはリソースの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-141">Gets or sets the location of the resource.</span></span>
            <span data-ttu-id="6965b-142">これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。</span><span class="sxs-lookup"><span data-stu-id="6965b-142">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="6965b-143">その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。</span><span class="sxs-lookup"><span data-stu-id="6965b-143">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6965b-144">取得または設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="6965b-144">Gets or sets required.</span></span> <span data-ttu-id="6965b-145">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-145">Gets or sets the sku name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6965b-146">取得またはリソースを説明するキー値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6965b-146">Gets or sets a list of key value pairs that describe the resource.</span></span>
            <span data-ttu-id="6965b-147">これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。</span><span class="sxs-lookup"><span data-stu-id="6965b-147">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="6965b-148">リソースの最大で 15 個のタグを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="6965b-148">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="6965b-149">各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。</span><span class="sxs-lookup"><span data-stu-id="6965b-149">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6965b-150">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6965b-150">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6965b-151">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6965b-151">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>