<Type Name="AzureMLLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMLLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureMLLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureML")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="54463-101">Azure ML Web サービスにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="54463-101">Azure ML Web Service linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.#ctor" />
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
            <span data-ttu-id="54463-102">AzureMLLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="54463-102">Initializes a new instance of the AzureMLLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService (object mlEndpoint, Microsoft.Azure.Management.DataFactory.Models.SecureString apiKey, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object updateResourceEndpoint = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object tenant = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object mlEndpoint, class Microsoft.Azure.Management.DataFactory.Models.SecureString apiKey, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object updateResourceEndpoint, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object tenant, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mlEndpoint As Object, apiKey As SecureString, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional updateResourceEndpoint As Object = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional tenant As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService : obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService (mlEndpoint, apiKey, additionalProperties, connectVia, description, updateResourceEndpoint, servicePrincipalId, servicePrincipalKey, tenant, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mlEndpoint" Type="System.Object" />
        <Parameter Name="apiKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="updateResourceEndpoint" Type="System.Object" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="mlEndpoint"><span data-ttu-id="54463-103">Azure ML Web サービス エンドポイントのバッチ実行 REST の URL です。</span><span class="sxs-lookup"><span data-stu-id="54463-103">The Batch Execution REST URL for an Azure ML Web Service endpoint.</span></span> <span data-ttu-id="54463-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="apiKey"><span data-ttu-id="54463-105">Azure ML モデル エンドポイントにアクセスするために API キー。</span><span class="sxs-lookup"><span data-stu-id="54463-105">The API key for accessing the Azure ML model endpoint.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="54463-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="54463-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="54463-107">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="54463-107">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="54463-108">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="54463-108">Linked service description.</span></span></param>
        <param name="updateResourceEndpoint"><span data-ttu-id="54463-109">Azure ML Web サービス エンドポイントの更新リソース REST の URL。</span><span class="sxs-lookup"><span data-stu-id="54463-109">The Update Resource REST URL for an Azure ML Web Service endpoint.</span></span> <span data-ttu-id="54463-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="servicePrincipalId"><span data-ttu-id="54463-111">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルの ID。</span><span class="sxs-lookup"><span data-stu-id="54463-111">The ID of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span> <span data-ttu-id="54463-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="servicePrincipalKey"><span data-ttu-id="54463-113">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキー。</span><span class="sxs-lookup"><span data-stu-id="54463-113">The key of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span></param>
        <param name="tenant"><span data-ttu-id="54463-114">名前またはサービス プリンシパルが属しているテナントの ID。</span><span class="sxs-lookup"><span data-stu-id="54463-114">The name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="54463-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="54463-116">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="54463-116">The encrypted credential used for authentication.</span></span> <span data-ttu-id="54463-117">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="54463-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="54463-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-118">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="54463-119">AzureMLLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="54463-119">Initializes a new instance of the AzureMLLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ApiKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.apiKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54463-120">取得または Azure ML モデル エンドポイントにアクセスするために API キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-120">Gets or sets the API key for accessing the Azure ML model endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="54463-121">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-121">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="54463-122">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="54463-122">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="54463-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MlEndpoint">
      <MemberSignature Language="C#" Value="public object MlEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MlEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MlEndpoint As Object" />
      <MemberSignature Language="F#" Value="member this.MlEndpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mlEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54463-124">取得または Azure ML Web サービス エンドポイントのバッチ実行 REST の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-124">Gets or sets the Batch Execution REST URL for an Azure ML Web Service endpoint.</span></span> <span data-ttu-id="54463-125">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalId" />
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
            <span data-ttu-id="54463-126">取得または Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用するサービス プリンシパルの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-126">Gets or sets the ID of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span> <span data-ttu-id="54463-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalKey" />
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
            <span data-ttu-id="54463-128">取得または Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-128">Gets or sets the key of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Tenant" />
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
            <span data-ttu-id="54463-129">取得または名またはサービス プリンシパルが属しているテナントの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-129">Gets or sets the name or ID of the tenant to which the service principal belongs.</span></span> <span data-ttu-id="54463-130">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-130">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateResourceEndpoint">
      <MemberSignature Language="C#" Value="public object UpdateResourceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UpdateResourceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateResourceEndpoint As Object" />
      <MemberSignature Language="F#" Value="member this.UpdateResourceEndpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.updateResourceEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54463-131">取得または Azure ML Web サービス エンドポイントの更新リソース REST の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="54463-131">Gets or sets the Update Resource REST URL for an Azure ML Web Service endpoint.</span></span> <span data-ttu-id="54463-132">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="54463-132">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMLLinkedService.Validate " />
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
            <span data-ttu-id="54463-133">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="54463-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54463-134">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54463-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>