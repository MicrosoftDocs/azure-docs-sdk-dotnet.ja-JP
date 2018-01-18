<Type Name="SparkLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService">
  <TypeSignature Language="C#" Value="public class SparkLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SparkLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SparkLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SparkLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Spark")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="291e3-101">Spark サーバーにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-101">Spark Server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="291e3-102">SparkLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="291e3-102">Initializes a new instance of the SparkLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService (object host, object port, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string serverType = null, string thriftTransportProtocol = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object httpPath = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, object port, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string serverType, string thriftTransportProtocol, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object httpPath, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor(System.Object,System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, port As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional serverType As String = null, Optional thriftTransportProtocol As String = null, Optional username As Object = null, Optional password As SecretBase = null, Optional httpPath As Object = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService : obj * obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService (host, port, authenticationType, additionalProperties, connectVia, description, serverType, thriftTransportProtocol, username, password, httpPath, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="serverType" Type="System.String" />
        <Parameter Name="thriftTransportProtocol" Type="System.String" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="httpPath" Type="System.Object" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="291e3-103">Spark サーバーの IP アドレスまたはホスト名</span><span class="sxs-lookup"><span data-stu-id="291e3-103">IP address or host name of the Spark server</span></span></param>
        <param name="port"><span data-ttu-id="291e3-104">Spark サーバーがクライアント接続のリッスンに使用する TCP ポート。</span><span class="sxs-lookup"><span data-stu-id="291e3-104">The TCP port that the Spark server uses to listen for client connections.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="291e3-105">Spark サーバーへのアクセスに使用する認証方法。</span><span class="sxs-lookup"><span data-stu-id="291e3-105">The authentication method used to access the Spark server.</span></span> <span data-ttu-id="291e3-106">使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。</span><span class="sxs-lookup"><span data-stu-id="291e3-106">Possible values include: 'Anonymous', 'Username', 'UsernameAndPassword', 'WindowsAzureHDInsightService'</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="291e3-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="291e3-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="291e3-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="291e3-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="291e3-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="291e3-109">Linked service description.</span></span></param>
        <param name="serverType"><span data-ttu-id="291e3-110">Spark サーバーの種類。</span><span class="sxs-lookup"><span data-stu-id="291e3-110">The type of Spark server.</span></span> <span data-ttu-id="291e3-111">使用可能な値が含まれます: 'SharkServer'、'SharkServer2'、'SparkThriftServer'</span><span class="sxs-lookup"><span data-stu-id="291e3-111">Possible values include: 'SharkServer', 'SharkServer2', 'SparkThriftServer'</span></span></param>
        <param name="thriftTransportProtocol"><span data-ttu-id="291e3-112">Thrift レイヤーで使用するトランスポート プロトコル。</span><span class="sxs-lookup"><span data-stu-id="291e3-112">The transport protocol to use in the Thrift layer.</span></span> <span data-ttu-id="291e3-113">使用可能な値が含まれます: 'Binary'、'SASL'、'HTTP'</span><span class="sxs-lookup"><span data-stu-id="291e3-113">Possible values include: 'Binary', 'SASL', 'HTTP '</span></span></param>
        <param name="username"><span data-ttu-id="291e3-114">Spark サーバーへのアクセスに使用するユーザー名。</span><span class="sxs-lookup"><span data-stu-id="291e3-114">The user name that you use to access Spark Server.</span></span></param>
        <param name="password"><span data-ttu-id="291e3-115">ユーザー名 フィールドで指定したユーザー名に対応するパスワード</span><span class="sxs-lookup"><span data-stu-id="291e3-115">The password corresponding to the user name that you provided in the Username field</span></span></param>
        <param name="httpPath"><span data-ttu-id="291e3-116">Spark サーバーに対応する部分的な URL。</span><span class="sxs-lookup"><span data-stu-id="291e3-116">The partial URL corresponding to the Spark server.</span></span></param>
        <param name="enableSsl"><span data-ttu-id="291e3-117">SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-117">Specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="291e3-118">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-118">The default value is false.</span></span></param>
        <param name="trustedCertPath"><span data-ttu-id="291e3-119">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。</span><span class="sxs-lookup"><span data-stu-id="291e3-119">The full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span> <span data-ttu-id="291e3-120">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="291e3-120">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="291e3-121">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="291e3-121">The default value is the cacerts.pem file installed with the IR.</span></span></param>
        <param name="useSystemTrustStore"><span data-ttu-id="291e3-122">システムの信頼ストアと指定した PEM ファイルのどちらの CA 証明書を使用するかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-122">Specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="291e3-123">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-123">The default value is false.</span></span></param>
        <param name="allowHostNameCNMismatch"><span data-ttu-id="291e3-124">SSL 経由で接続するときに、CA が発行した SSL 証明書名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-124">Specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="291e3-125">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-125">The default value is false.</span></span></param>
        <param name="allowSelfSignedServerCert"><span data-ttu-id="291e3-126">サーバーからの自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-126">Specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="291e3-127">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-127">The default value is false.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="291e3-128">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="291e3-128">The encrypted credential used for authentication.</span></span> <span data-ttu-id="291e3-129">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="291e3-129">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="291e3-130">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="291e3-130">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="291e3-131">SparkLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="291e3-131">Initializes a new instance of the SparkLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowHostNameCNMismatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-132">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように CA から発行される SSL 証明書名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-132">Gets or sets specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="291e3-133">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-133">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowSelfSignedServerCert")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-134">取得または設定は、サーバーから自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-134">Gets or sets specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="291e3-135">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-135">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
            <span data-ttu-id="291e3-136">取得または Spark サーバーへのアクセスに使用する認証方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-136">Gets or sets the authentication method used to access the Spark server.</span></span> <span data-ttu-id="291e3-137">使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。</span><span class="sxs-lookup"><span data-stu-id="291e3-137">Possible values include: 'Anonymous', 'Username', 'UsernameAndPassword', 'WindowsAzureHDInsightService'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableSsl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-138">取得または設定は、SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-138">Gets or sets specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="291e3-139">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-139">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="291e3-140">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-140">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="291e3-141">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="291e3-141">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="291e3-142">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="291e3-142">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-143">取得または設定、Spark サーバーの IP アドレスまたはホスト名</span><span class="sxs-lookup"><span data-stu-id="291e3-143">Gets or sets IP address or host name of the Spark server</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.httpPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-144">取得または Spark サーバーに対応する部分的な URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-144">Gets or sets the partial URL corresponding to the Spark server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
            <span data-ttu-id="291e3-145">取得またはユーザー名 フィールドで指定したユーザー名に対応するパスワードを設定</span><span class="sxs-lookup"><span data-stu-id="291e3-145">Gets or sets the password corresponding to the user name that you provided in the Username field</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-146">取得または Spark サーバーがクライアント接続のリッスンに使用される TCP ポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-146">Gets or sets the TCP port that the Spark server uses to listen for client connections.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerType">
      <MemberSignature Language="C#" Value="public string ServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerType As String" />
      <MemberSignature Language="F#" Value="member this.ServerType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serverType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-147">取得または Spark サーバーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-147">Gets or sets the type of Spark server.</span></span> <span data-ttu-id="291e3-148">使用可能な値が含まれます: 'SharkServer'、'SharkServer2'、'SparkThriftServer'</span><span class="sxs-lookup"><span data-stu-id="291e3-148">Possible values include: 'SharkServer', 'SharkServer2', 'SparkThriftServer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThriftTransportProtocol">
      <MemberSignature Language="C#" Value="public string ThriftTransportProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThriftTransportProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property ThriftTransportProtocol As String" />
      <MemberSignature Language="F#" Value="member this.ThriftTransportProtocol : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.thriftTransportProtocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-149">取得または Thrift レイヤーを使用するトランスポート プロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-149">Gets or sets the transport protocol to use in the Thrift layer.</span></span>
            <span data-ttu-id="291e3-150">使用可能な値が含まれます: 'Binary'、'SASL'、'HTTP'</span><span class="sxs-lookup"><span data-stu-id="291e3-150">Possible values include: 'Binary', 'SASL', 'HTTP '</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trustedCertPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-151">取得または SSL 経由で接続するときに、サーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-151">Gets or sets the full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span>
            <span data-ttu-id="291e3-152">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="291e3-152">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="291e3-153">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="291e3-153">The default value is the cacerts.pem file installed with the IR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
            <span data-ttu-id="291e3-154">取得または Spark サーバーへのアクセスに使用するユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-154">Gets or sets the user name that you use to access Spark Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useSystemTrustStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="291e3-155">取得または設定は、システムのトラスト ストアから、または指定した PEM ファイルから CA 証明書を使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="291e3-155">Gets or sets specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="291e3-156">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="291e3-156">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sparkLinkedService.Validate " />
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
            <span data-ttu-id="291e3-157">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="291e3-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="291e3-158">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="291e3-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>