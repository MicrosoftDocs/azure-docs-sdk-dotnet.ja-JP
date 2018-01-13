<Type Name="HttpLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService">
  <TypeSignature Language="C#" Value="public class HttpLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HttpLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HttpServer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="74996-101">HTTP ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="74996-101">Linked service for an HTTP source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.#ctor" />
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
            <span data-ttu-id="74996-102">HttpLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74996-102">Initializes a new instance of the HttpLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService (object url, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string authenticationType = null, object userName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object embeddedCertData = null, object certThumbprint = null, object encryptedCredential = null, object enableServerCertificateValidation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string authenticationType, object userName, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object embeddedCertData, object certThumbprint, object encryptedCredential, object enableServerCertificateValidation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional authenticationType As String = null, Optional userName As Object = null, Optional password As SecureString = null, Optional embeddedCertData As Object = null, Optional certThumbprint As Object = null, Optional encryptedCredential As Object = null, Optional enableServerCertificateValidation As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService (url, additionalProperties, connectVia, description, authenticationType, userName, password, embeddedCertData, certThumbprint, encryptedCredential, enableServerCertificateValidation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="userName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="embeddedCertData" Type="System.Object" />
        <Parameter Name="certThumbprint" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
        <Parameter Name="enableServerCertificateValidation" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="74996-103">例: http://www.microsoft.com、HTTP エンドポイントのベース URL。型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-103">The base URL of the HTTP endpoint, e.g. http://www.microsoft.com. Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="74996-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="74996-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="74996-105">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="74996-105">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="74996-106">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="74996-106">Linked service description.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="74996-107">HTTP サーバーへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="74996-107">The authentication type to be used to connect to the HTTP server.</span></span> <span data-ttu-id="74996-108">使用可能な値が含まれます: 'Basic'、'Anonymous'、'ダイジェスト'、'Windows'、'ClientCertificate'</span><span class="sxs-lookup"><span data-stu-id="74996-108">Possible values include: 'Basic', 'Anonymous', 'Digest', 'Windows', 'ClientCertificate'</span></span></param>
        <param name="userName"><span data-ttu-id="74996-109">基本認証、ダイジェスト認証、または Windows 認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="74996-109">User name for Basic, Digest, or Windows authentication.</span></span> <span data-ttu-id="74996-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="74996-111">EmbeddedCertData 認証と基本認証、ダイジェスト、Windows、または ClientCertificate のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="74996-111">Password for Basic, Digest, Windows, or ClientCertificate with EmbeddedCertData authentication.</span></span></param>
        <param name="embeddedCertData"><span data-ttu-id="74996-112">ClientCertificate 認証用の証明書データを Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="74996-112">Base64 encoded certificate data for ClientCertificate authentication.</span></span> <span data-ttu-id="74996-113">ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="74996-113">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span> <span data-ttu-id="74996-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="certThumbprint"><span data-ttu-id="74996-115">ClientCertificate 認証用の証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="74996-115">Thumbprint of certificate for ClientCertificate authentication.</span></span> <span data-ttu-id="74996-116">内部設置型のコピーに対してのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="74996-116">Only valid for on-premises copy.</span></span>
            <span data-ttu-id="74996-117">ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="74996-117">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span>
            <span data-ttu-id="74996-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="74996-119">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="74996-119">The encrypted credential used for authentication.</span></span> <span data-ttu-id="74996-120">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="74996-120">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="74996-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-121">Type: string (or Expression with resultType string).</span></span></param>
        <param name="enableServerCertificateValidation"><span data-ttu-id="74996-122">True の場合は、HTTPS サーバー SSL 証明書を検証します。</span><span class="sxs-lookup"><span data-stu-id="74996-122">If true, validate the HTTPS server SSL certificate.</span></span> <span data-ttu-id="74996-123">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="74996-123">Default value is true.</span></span> <span data-ttu-id="74996-124">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="74996-124">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="74996-125">HttpLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74996-125">Initializes a new instance of the HttpLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-126">取得または HTTP サーバーへの接続に使用する認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-126">Gets or sets the authentication type to be used to connect to the HTTP server.</span></span> <span data-ttu-id="74996-127">使用可能な値が含まれます: 'Basic'、'Anonymous'、'ダイジェスト'、'Windows'、'ClientCertificate'</span><span class="sxs-lookup"><span data-stu-id="74996-127">Possible values include: 'Basic', 'Anonymous', 'Digest', 'Windows', 'ClientCertificate'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertThumbprint">
      <MemberSignature Language="C#" Value="public object CertThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.CertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertThumbprint As Object" />
      <MemberSignature Language="F#" Value="member this.CertThumbprint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.CertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.certThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-128">取得または ClientCertificate 認証用の証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-128">Gets or sets thumbprint of certificate for ClientCertificate authentication.</span></span> <span data-ttu-id="74996-129">内部設置型のコピーに対してのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="74996-129">Only valid for on-premises copy.</span></span> <span data-ttu-id="74996-130">ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="74996-130">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span> <span data-ttu-id="74996-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmbeddedCertData">
      <MemberSignature Language="C#" Value="public object EmbeddedCertData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EmbeddedCertData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberSignature Language="VB.NET" Value="Public Property EmbeddedCertData As Object" />
      <MemberSignature Language="F#" Value="member this.EmbeddedCertData : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.embeddedCertData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-132">取得または ClientCertificate 認証用の base64 でエンコードされた証明書データを設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-132">Gets or sets base64 encoded certificate data for ClientCertificate authentication.</span></span> <span data-ttu-id="74996-133">ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="74996-133">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span> <span data-ttu-id="74996-134">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-134">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableServerCertificateValidation">
      <MemberSignature Language="C#" Value="public object EnableServerCertificateValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableServerCertificateValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableServerCertificateValidation As Object" />
      <MemberSignature Language="F#" Value="member this.EnableServerCertificateValidation : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableServerCertificateValidation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-135">取得または設定が true の場合は、HTTPS サーバー SSL 証明書を検証します。</span><span class="sxs-lookup"><span data-stu-id="74996-135">Gets or sets if true, validate the HTTPS server SSL certificate.</span></span>
            <span data-ttu-id="74996-136">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="74996-136">Default value is true.</span></span> <span data-ttu-id="74996-137">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="74996-137">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="74996-138">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-138">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="74996-139">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="74996-139">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="74996-140">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-140">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.Password" />
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
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-141">取得または基本認証、ダイジェスト、Windows、または ClientCertificate の EmbeddedCertData 認証でのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-141">Gets or sets password for Basic, Digest, Windows, or ClientCertificate with EmbeddedCertData authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public object Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As Object" />
      <MemberSignature Language="F#" Value="member this.Url : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-142">取得または http://www.microsoft.com など、HTTP エンドポイントのベース URL を設定します。型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-142">Gets or sets the base URL of the HTTP endpoint, e.g. http://www.microsoft.com. Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public object UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As Object" />
      <MemberSignature Language="F#" Value="member this.UserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.userName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74996-143">取得または基本認証、ダイジェスト認証、または Windows 認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="74996-143">Gets or sets user name for Basic, Digest, or Windows authentication.</span></span> <span data-ttu-id="74996-144">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="74996-144">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="httpLinkedService.Validate " />
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
            <span data-ttu-id="74996-145">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="74996-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74996-146">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="74996-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>