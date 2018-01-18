<Type Name="AzureDataLakeStoreLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureDataLakeStore")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="48270-101">Azure Data Lake Store のリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="48270-101">Azure Data Lake Store linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.#ctor" />
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
            <span data-ttu-id="48270-102">Azuredatalakestorelinkedservice でクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="48270-102">Initializes a new instance of the AzureDataLakeStoreLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreLinkedService (object dataLakeStoreUri, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object tenant = null, object accountName = null, object subscriptionId = null, object resourceGroupName = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object dataLakeStoreUri, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object tenant, object accountName, object subscriptionId, object resourceGroupName, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLakeStoreUri As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional tenant As Object = null, Optional accountName As Object = null, Optional subscriptionId As Object = null, Optional resourceGroupName As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService (dataLakeStoreUri, additionalProperties, connectVia, description, servicePrincipalId, servicePrincipalKey, tenant, accountName, subscriptionId, resourceGroupName, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLakeStoreUri" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="accountName" Type="System.Object" />
        <Parameter Name="subscriptionId" Type="System.Object" />
        <Parameter Name="resourceGroupName" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="dataLakeStoreUri"><span data-ttu-id="48270-103">Data Lake Store サービス URI です。</span><span class="sxs-lookup"><span data-stu-id="48270-103">Data Lake Store service URI.</span></span> <span data-ttu-id="48270-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="48270-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="48270-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="48270-106">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="48270-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="48270-107">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="48270-107">Linked service description.</span></span></param>
        <param name="servicePrincipalId"><span data-ttu-id="48270-108">Azure Data Lake Store アカウントに対する認証に使用されるアプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="48270-108">The ID of the application used to authenticate against the Azure Data Lake Store account.</span></span> <span data-ttu-id="48270-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="servicePrincipalKey"><span data-ttu-id="48270-110">Azure Data Lake Store アカウントに対する認証に使用されるアプリケーションのキー。</span><span class="sxs-lookup"><span data-stu-id="48270-110">The Key of the application used to authenticate against the Azure Data Lake Store account.</span></span></param>
        <param name="tenant"><span data-ttu-id="48270-111">名前またはサービス プリンシパルが属しているテナントの ID。</span><span class="sxs-lookup"><span data-stu-id="48270-111">The name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="48270-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="accountName"><span data-ttu-id="48270-113">Data Lake Store アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="48270-113">Data Lake Store account name.</span></span> <span data-ttu-id="48270-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="48270-115">Data Lake Store アカウント サブスクリプション ID (Data Factory アカウントとは異なる) 場合です。</span><span class="sxs-lookup"><span data-stu-id="48270-115">Data Lake Store account subscription ID (if different from Data Factory account).</span></span> <span data-ttu-id="48270-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="resourceGroupName"><span data-ttu-id="48270-117">Data Lake Store アカウント リソース グループ名 (Data Factory アカウントとは異なる) 場合。</span><span class="sxs-lookup"><span data-stu-id="48270-117">Data Lake Store account resource group name (if different from Data Factory account).</span></span> <span data-ttu-id="48270-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="48270-119">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="48270-119">The encrypted credential used for authentication.</span></span> <span data-ttu-id="48270-120">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="48270-120">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="48270-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-121">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="48270-122">Azuredatalakestorelinkedservice でクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="48270-122">Initializes a new instance of the AzureDataLakeStoreLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public object AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As Object" />
      <MemberSignature Language="F#" Value="member this.AccountName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.AccountName" />
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
            <span data-ttu-id="48270-123">取得またはデータ Lake Store アカウント名を設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-123">Gets or sets data Lake Store account name.</span></span> <span data-ttu-id="48270-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreUri">
      <MemberSignature Language="C#" Value="public object DataLakeStoreUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DataLakeStoreUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.DataLakeStoreUri" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeStoreUri As Object" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreUri : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.DataLakeStoreUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.dataLakeStoreUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="48270-125">取得またはデータ Lake Store サービス URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-125">Gets or sets data Lake Store service URI.</span></span> <span data-ttu-id="48270-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="48270-127">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-127">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="48270-128">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="48270-128">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="48270-129">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-129">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public object ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As Object" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ResourceGroupName" />
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
            <span data-ttu-id="48270-130">取得または設定 data Lake Store アカウント リソース グループ名 (Data Factory アカウントとは異なる) 場合。</span><span class="sxs-lookup"><span data-stu-id="48270-130">Gets or sets data Lake Store account resource group name (if different from Data Factory account).</span></span> <span data-ttu-id="48270-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ServicePrincipalId" />
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
            <span data-ttu-id="48270-132">取得または Azure Data Lake Store アカウントに対する認証に使用されるアプリケーションの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-132">Gets or sets the ID of the application used to authenticate against the Azure Data Lake Store account.</span></span> <span data-ttu-id="48270-133">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-133">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.ServicePrincipalKey" />
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
            <span data-ttu-id="48270-134">取得または Azure Data Lake Store アカウントに対する認証に使用するアプリケーションのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-134">Gets or sets the Key of the application used to authenticate against the Azure Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public object SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As Object" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.SubscriptionId" />
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
            <span data-ttu-id="48270-135">取得または設定データ Lake Store アカウント サブスクリプション ID (Data Factory アカウントとは異なる) 場合。</span><span class="sxs-lookup"><span data-stu-id="48270-135">Gets or sets data Lake Store account subscription ID (if different from Data Factory account).</span></span> <span data-ttu-id="48270-136">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-136">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.Tenant" />
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
            <span data-ttu-id="48270-137">取得または名またはサービス プリンシパルが属しているテナントの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="48270-137">Gets or sets the name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="48270-138">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="48270-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureDataLakeStoreLinkedService.Validate " />
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
            <span data-ttu-id="48270-139">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="48270-139">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="48270-140">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="48270-140">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>