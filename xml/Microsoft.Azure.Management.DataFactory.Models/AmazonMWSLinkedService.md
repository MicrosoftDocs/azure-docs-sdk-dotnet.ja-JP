<Type Name="AmazonMWSLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService">
  <TypeSignature Language="C#" Value="public class AmazonMWSLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonMWSLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonMWSLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AmazonMWSLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
      <AttributeName>Newtonsoft.Json.JsonObject("AmazonMWS")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7aecf-101">Amazon Marketplace Web サービスにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-101">Amazon Marketplace Web Service linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-102">AmazonMWSLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-102">Initializes a new instance of the AmazonMWSLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService (object endpoint, object marketplaceID, object sellerID, object accessKeyId, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object endpoint, object marketplaceID, object sellerID, object accessKeyId, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken, class Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor(System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Object, marketplaceID As Object, sellerID As Object, accessKeyId As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional mwsAuthToken As SecretBase = null, Optional secretKey As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService : obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService (endpoint, marketplaceID, sellerID, accessKeyId, additionalProperties, connectVia, description, mwsAuthToken, secretKey, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Object" />
        <Parameter Name="marketplaceID" Type="System.Object" />
        <Parameter Name="sellerID" Type="System.Object" />
        <Parameter Name="accessKeyId" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="mwsAuthToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="secretKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="7aecf-103">Amazon MWS サーバー (つまり mws.amazonservices.com) のエンドポイント</span><span class="sxs-lookup"><span data-stu-id="7aecf-103">The endpoint of the Amazon MWS server, (i.e. mws.amazonservices.com)</span></span></param>
        <param name="marketplaceID"><span data-ttu-id="7aecf-104">データを取得する Amazon Marketplace ID。</span><span class="sxs-lookup"><span data-stu-id="7aecf-104">The Amazon Marketplace ID you want to retrieve data from.</span></span> <span data-ttu-id="7aecf-105">複数の Id は Marketplace からのデータを取得は、コンマ (,) で区切ります。</span><span class="sxs-lookup"><span data-stu-id="7aecf-105">To retrive data from multiple Marketplace IDs, seperate them with a comma (,).</span></span> <span data-ttu-id="7aecf-106">(つまり A2EUQ1WTGCTBG2)</span><span class="sxs-lookup"><span data-stu-id="7aecf-106">(i.e. A2EUQ1WTGCTBG2)</span></span></param>
        <param name="sellerID"><span data-ttu-id="7aecf-107">Amazon の販売者 ID。</span><span class="sxs-lookup"><span data-stu-id="7aecf-107">The Amazon seller ID.</span></span></param>
        <param name="accessKeyId"><span data-ttu-id="7aecf-108">データにアクセスするためのアクセス キー id です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-108">The access key id used to access data.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="7aecf-109">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="7aecf-109">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="7aecf-110">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="7aecf-110">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="7aecf-111">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="7aecf-111">Linked service description.</span></span></param>
        <param name="mwsAuthToken"><span data-ttu-id="7aecf-112">Amazon MWS 認証トークン。</span><span class="sxs-lookup"><span data-stu-id="7aecf-112">The Amazon MWS authentication token.</span></span></param>
        <param name="secretKey"><span data-ttu-id="7aecf-113">データのアクセスに使用されるシークレット キー。</span><span class="sxs-lookup"><span data-stu-id="7aecf-113">The secret key used to access data.</span></span></param>
        <param name="useEncryptedEndpoints"><span data-ttu-id="7aecf-114">データ ソースのエンドポイントが HTTPS を使用して暗号化されるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-114">Specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="7aecf-115">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-115">The default value is true.</span></span></param>
        <param name="useHostVerification"><span data-ttu-id="7aecf-116">SSL 経由で接続するときに、サーバーの証明書内のホスト名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-116">Specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="7aecf-117">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-117">The default value is true.</span></span></param>
        <param name="usePeerVerification"><span data-ttu-id="7aecf-118">SSL 経由で接続するときに、サーバーの ID を検証するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-118">Specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="7aecf-119">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-119">The default value is true.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="7aecf-120">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-120">The encrypted credential used for authentication.</span></span> <span data-ttu-id="7aecf-121">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="7aecf-121">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="7aecf-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7aecf-122">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="7aecf-123">AmazonMWSLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-123">Initializes a new instance of the AmazonMWSLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeyId">
      <MemberSignature Language="C#" Value="public object AccessKeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccessKeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKeyId As Object" />
      <MemberSignature Language="F#" Value="member this.AccessKeyId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessKeyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-124">取得またはデータにアクセスするためのアクセス キー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-124">Gets or sets the access key id used to access data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
            <span data-ttu-id="7aecf-125">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-125">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="7aecf-126">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="7aecf-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="7aecf-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7aecf-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public object Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Object" />
      <MemberSignature Language="F#" Value="member this.Endpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-128">取得または設定 (つまり mws.amazonservices.com)、Amazon MWS サーバーのエンドポイント</span><span class="sxs-lookup"><span data-stu-id="7aecf-128">Gets or sets the endpoint of the Amazon MWS server, (i.e. mws.amazonservices.com)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplaceID">
      <MemberSignature Language="C#" Value="public object MarketplaceID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MarketplaceID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberSignature Language="VB.NET" Value="Public Property MarketplaceID As Object" />
      <MemberSignature Language="F#" Value="member this.MarketplaceID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.marketplaceID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-129">ID 取得または設定、Amazon Marketplace からデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-129">Gets or sets the Amazon Marketplace ID you want to retrieve data from.</span></span> <span data-ttu-id="7aecf-130">複数の Id は Marketplace からのデータを取得は、コンマ (,) で区切ります。</span><span class="sxs-lookup"><span data-stu-id="7aecf-130">To retrive data from multiple Marketplace IDs, seperate them with a comma (,).</span></span> <span data-ttu-id="7aecf-131">(つまり A2EUQ1WTGCTBG2)</span><span class="sxs-lookup"><span data-stu-id="7aecf-131">(i.e. A2EUQ1WTGCTBG2)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MwsAuthToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberSignature Language="VB.NET" Value="Public Property MwsAuthToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.MwsAuthToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mwsAuthToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-132">取得または Amazon MWS 認証トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-132">Gets or sets the Amazon MWS authentication token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As SecretBase" />
      <MemberSignature Language="F#" Value="member this.SecretKey : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.secretKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-133">取得またはデータへのアクセスに使用する秘密キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-133">Gets or sets the secret key used to access data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SellerID">
      <MemberSignature Language="C#" Value="public object SellerID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SellerID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberSignature Language="VB.NET" Value="Public Property SellerID As Object" />
      <MemberSignature Language="F#" Value="member this.SellerID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sellerID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-134">取得または設定、Amazon の販売者 id です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-134">Gets or sets the Amazon seller ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useEncryptedEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-135">取得または設定は、データ ソースのエンドポイントは HTTPS を使用して暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-135">Gets or sets specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="7aecf-136">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-136">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useHostVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-137">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように、サーバーの証明書内のホスト名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-137">Gets or sets specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="7aecf-138">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-138">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.usePeerVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-139">取得または設定は、SSL 経由で接続するときに、サーバーの id を確認するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-139">Gets or sets specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="7aecf-140">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7aecf-140">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="amazonMWSLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7aecf-141">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7aecf-141">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7aecf-142">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7aecf-142">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>