<Type Name="AzureDataLakeAnalyticsLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService">
  <TypeSignature Language="C#" Value="public class AzureDataLakeAnalyticsLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeAnalyticsLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeAnalyticsLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureDataLakeAnalyticsLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureDataLakeAnalytics")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3f0e9-101">Azure Data Lake Analytics には、サービスがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-101">Azure Data Lake Analytics linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeAnalyticsLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-102">AzureDataLakeAnalyticsLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-102">Initializes a new instance of the AzureDataLakeAnalyticsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeAnalyticsLinkedService (object accountName, object tenant, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object subscriptionId = null, object resourceGroupName = null, object dataLakeAnalyticsUri = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object accountName, object tenant, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object subscriptionId, object resourceGroupName, object dataLakeAnalyticsUri, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As Object, tenant As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional subscriptionId As Object = null, Optional resourceGroupName As Object = null, Optional dataLakeAnalyticsUri As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService (accountName, tenant, additionalProperties, connectVia, description, servicePrincipalId, servicePrincipalKey, subscriptionId, resourceGroupName, dataLakeAnalyticsUri, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.Object" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="subscriptionId" Type="System.Object" />
        <Parameter Name="resourceGroupName" Type="System.Object" />
        <Parameter Name="dataLakeAnalyticsUri" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="3f0e9-103">Azure Data Lake Analytics アカウント名。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-103">The Azure Data Lake Analytics account name.</span></span> <span data-ttu-id="3f0e9-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="tenant"><span data-ttu-id="3f0e9-105">名前またはサービス プリンシパルが属しているテナントの ID。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-105">The name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="3f0e9-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="3f0e9-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="3f0e9-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="3f0e9-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="3f0e9-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-109">Linked service description.</span></span></param>
        <param name="servicePrincipalId"><span data-ttu-id="3f0e9-110">Azure Data Lake Analytics アカウントに対する認証に使用されるアプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-110">The ID of the application used to authenticate against the Azure Data Lake Analytics account.</span></span> <span data-ttu-id="3f0e9-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="servicePrincipalKey"><span data-ttu-id="3f0e9-112">Azure Data Lake Analytics アカウントに対する認証に使用されるアプリケーションのキー。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-112">The Key of the application used to authenticate against the Azure Data Lake Analytics account.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="3f0e9-113">(Data Factory アカウントとは異なる) 場合、data Lake Analytics アカウント サブスクリプション ID。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-113">Data Lake Analytics account subscription ID (if different from Data Factory account).</span></span> <span data-ttu-id="3f0e9-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="resourceGroupName"><span data-ttu-id="3f0e9-115">Data Lake Analytics アカウント リソース グループ名の (Data Factory アカウントとは異なる) 場合。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-115">Data Lake Analytics account resource group name (if different from Data Factory account).</span></span> <span data-ttu-id="3f0e9-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="dataLakeAnalyticsUri"><span data-ttu-id="3f0e9-117">Azure データ Lake Analytics URI 型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-117">Azure Data Lake Analytics URI Type: string (or Expression with resultType string).</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="3f0e9-118">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-118">The encrypted credential used for authentication.</span></span> <span data-ttu-id="3f0e9-119">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-119">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="3f0e9-120">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-120">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="3f0e9-121">AzureDataLakeAnalyticsLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-121">Initializes a new instance of the AzureDataLakeAnalyticsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public object AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As Object" />
      <MemberSignature Language="F#" Value="member this.AccountName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-122">取得または Azure Data Lake Analytics アカウント名を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-122">Gets or sets the Azure Data Lake Analytics account name.</span></span> <span data-ttu-id="3f0e9-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeAnalyticsUri">
      <MemberSignature Language="C#" Value="public object DataLakeAnalyticsUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DataLakeAnalyticsUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.DataLakeAnalyticsUri" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeAnalyticsUri As Object" />
      <MemberSignature Language="F#" Value="member this.DataLakeAnalyticsUri : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.DataLakeAnalyticsUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.dataLakeAnalyticsUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-124">Azure データ Lake Analytics URI 型取得または設定します。 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-124">Gets or sets azure Data Lake Analytics URI Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-125">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-125">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="3f0e9-126">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="3f0e9-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public object ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As Object" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.resourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-128">取得または (Data Factory アカウントとは異なる) 場合に、data Lake Analytics アカウント リソース グループ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-128">Gets or sets data Lake Analytics account resource group name (if different from Data Factory account).</span></span> <span data-ttu-id="3f0e9-129">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-129">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-130">取得または Azure Data Lake Analytics アカウントに対する認証に使用されるアプリケーションの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-130">Gets or sets the ID of the application used to authenticate against the Azure Data Lake Analytics account.</span></span> <span data-ttu-id="3f0e9-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-132">取得または Azure Data Lake Analytics アカウントに対する認証に使用するアプリケーションのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-132">Gets or sets the Key of the application used to authenticate against the Azure Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public object SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As Object" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-133">取得または (Data Factory アカウントとは異なる) 場合は、データ Lake Analytics アカウント サブスクリプション ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-133">Gets or sets data Lake Analytics account subscription ID (if different from Data Factory account).</span></span> <span data-ttu-id="3f0e9-134">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-134">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tenant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-135">取得または名またはサービス プリンシパルが属しているテナントの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-135">Gets or sets the name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="3f0e9-136">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-136">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeAnalyticsLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureDataLakeAnalyticsLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f0e9-137">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-137">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3f0e9-138">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3f0e9-138">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>