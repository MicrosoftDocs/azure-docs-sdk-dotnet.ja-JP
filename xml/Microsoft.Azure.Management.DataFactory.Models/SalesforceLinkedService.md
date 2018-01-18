<Type Name="SalesforceLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService">
  <TypeSignature Language="C#" Value="public class SalesforceLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SalesforceLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SalesforceLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SalesforceLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Salesforce")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7d6c0-101">Salesforce のリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-101">Linked service for Salesforce.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.#ctor" />
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
            <span data-ttu-id="7d6c0-102">SalesforceLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-102">Initializes a new instance of the SalesforceLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceLinkedService (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object environmentUrl = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase securityToken = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object environmentUrl, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, class Microsoft.Azure.Management.DataFactory.Models.SecretBase securityToken, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional environmentUrl As Object = null, Optional username As Object = null, Optional password As SecretBase = null, Optional securityToken As SecretBase = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService : System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService (additionalProperties, connectVia, description, environmentUrl, username, password, securityToken, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="environmentUrl" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="securityToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="7d6c0-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="7d6c0-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="7d6c0-104">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-104">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="7d6c0-105">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-105">Linked service description.</span></span></param>
        <param name="environmentUrl"><span data-ttu-id="7d6c0-106">URL の Salesforce のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-106">The URL of Salesforce instance.</span></span>
            <span data-ttu-id="7d6c0-107">既定値は、'https://login.salesforce.com' です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-107">Default is 'https://login.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-108">サンド ボックスからデータをコピーするには、'https://test.salesforce.com' を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-108">To copy data from sandbox, specify 'https://test.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-109">カスタム ドメインからデータをコピーするに指定するには、'https://[domain].my.salesforce.com' です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-109">To copy data from custom domain, specify, for example, 'https://[domain].my.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="username"><span data-ttu-id="7d6c0-111">Salesforce インスタンスの基本認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-111">The username for Basic authentication of the Salesforce instance.</span></span> <span data-ttu-id="7d6c0-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="7d6c0-113">Salesforce インスタンスの基本認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-113">The password for Basic authentication of the Salesforce instance.</span></span></param>
        <param name="securityToken"><span data-ttu-id="7d6c0-114">Salesforce インスタンスにリモートでアクセスするには、セキュリティ トークンが必要です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-114">The security token is required to remotely access Salesforce instance.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="7d6c0-115">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-115">The encrypted credential used for authentication.</span></span> <span data-ttu-id="7d6c0-116">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-116">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="7d6c0-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-117">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="7d6c0-118">SalesforceLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-118">Initializes a new instance of the SalesforceLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="7d6c0-119">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-119">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="7d6c0-120">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-120">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="7d6c0-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentUrl">
      <MemberSignature Language="C#" Value="public object EnvironmentUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnvironmentUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.EnvironmentUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentUrl As Object" />
      <MemberSignature Language="F#" Value="member this.EnvironmentUrl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.EnvironmentUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.environmentUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d6c0-122">取得または URL の Salesforce のインスタンスを設定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-122">Gets or sets the URL of Salesforce instance.</span></span> <span data-ttu-id="7d6c0-123">既定値は、'https://login.salesforce.com' です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-123">Default is 'https://login.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-124">サンド ボックスからデータをコピーするには、'https://test.salesforce.com' を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-124">To copy data from sandbox, specify 'https://test.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-125">カスタム ドメインからデータをコピーするに指定するには、'https://[domain].my.salesforce.com' です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-125">To copy data from custom domain, specify, for example, 'https://[domain].my.salesforce.com'.</span></span> <span data-ttu-id="7d6c0-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d6c0-127">取得または Salesforce インスタンスの基本認証用のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-127">Gets or sets the password for Basic authentication of the Salesforce instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase SecurityToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase SecurityToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.SecurityToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.SecurityToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.SecurityToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.securityToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d6c0-128">取得または設定、セキュリティ トークンは Salesforce のインスタンスにリモート アクセスするために必要です。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-128">Gets or sets the security token is required to remotely access Salesforce instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d6c0-129">取得または Salesforce インスタンスの基本認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-129">Gets or sets the username for Basic authentication of the Salesforce instance.</span></span> <span data-ttu-id="7d6c0-130">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-130">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="salesforceLinkedService.Validate " />
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
            <span data-ttu-id="7d6c0-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d6c0-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d6c0-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>