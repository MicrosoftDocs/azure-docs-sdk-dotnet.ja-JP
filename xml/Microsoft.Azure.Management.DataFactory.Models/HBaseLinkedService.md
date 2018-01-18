<Type Name="HBaseLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService">
  <TypeSignature Language="C#" Value="public class HBaseLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HBaseLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HBaseLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HBaseLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HBase")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="79c49-101">HBase サーバーにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-101">HBase server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HBaseLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="79c49-102">HBaseLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="79c49-102">Initializes a new instance of the HBaseLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HBaseLinkedService (object host, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, object httpPath = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object enableSsl = null, object trustedCertPath = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, object httpPath, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object enableSsl, object trustedCertPath, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.#ctor(System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional httpPath As Object = null, Optional username As Object = null, Optional password As SecretBase = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService : obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService (host, authenticationType, additionalProperties, connectVia, description, port, httpPath, username, password, enableSsl, trustedCertPath, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="httpPath" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="79c49-103">HBase サーバーの IP アドレスまたはホスト名。</span><span class="sxs-lookup"><span data-stu-id="79c49-103">The IP address or host name of the HBase server.</span></span>
            <span data-ttu-id="79c49-104">(例: 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="79c49-104">(i.e. 192.168.222.160)</span></span></param>
        <param name="authenticationType"><span data-ttu-id="79c49-105">HBase サーバーへの接続に使用する認証メカニズム。</span><span class="sxs-lookup"><span data-stu-id="79c49-105">The authentication mechanism to use to connect to the HBase server.</span></span> <span data-ttu-id="79c49-106">使用可能な値が含まれます 'Anonymous'、'Basic'。</span><span class="sxs-lookup"><span data-stu-id="79c49-106">Possible values include: 'Anonymous', 'Basic'</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="79c49-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="79c49-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="79c49-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="79c49-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="79c49-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="79c49-109">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="79c49-110">HBase インスタンスがクライアント接続のリッスンに使用する TCP ポート。</span><span class="sxs-lookup"><span data-stu-id="79c49-110">The TCP port that the HBase instance uses to listen for client connections.</span></span> <span data-ttu-id="79c49-111">既定値は 9090 です。</span><span class="sxs-lookup"><span data-stu-id="79c49-111">The default value is 9090.</span></span></param>
        <param name="httpPath"><span data-ttu-id="79c49-112">HBase サーバーに対応する部分的な URL。</span><span class="sxs-lookup"><span data-stu-id="79c49-112">The partial URL corresponding to the HBase server.</span></span> <span data-ttu-id="79c49-113">(/gateway/sandbox/hbase/version など)</span><span class="sxs-lookup"><span data-stu-id="79c49-113">(i.e. /gateway/sandbox/hbase/version)</span></span></param>
        <param name="username"><span data-ttu-id="79c49-114">HBase インスタンスへの接続に使用されるユーザー名。</span><span class="sxs-lookup"><span data-stu-id="79c49-114">The user name used to connect to the HBase instance.</span></span></param>
        <param name="password"><span data-ttu-id="79c49-115">ユーザー名に対応するパスワード。</span><span class="sxs-lookup"><span data-stu-id="79c49-115">The password corresponding to the user name.</span></span></param>
        <param name="enableSsl"><span data-ttu-id="79c49-116">SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-116">Specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="79c49-117">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-117">The default value is false.</span></span></param>
        <param name="trustedCertPath"><span data-ttu-id="79c49-118">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。</span><span class="sxs-lookup"><span data-stu-id="79c49-118">The full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span> <span data-ttu-id="79c49-119">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="79c49-119">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="79c49-120">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="79c49-120">The default value is the cacerts.pem file installed with the IR.</span></span></param>
        <param name="allowHostNameCNMismatch"><span data-ttu-id="79c49-121">SSL 経由で接続するときに、CA が発行した SSL 証明書名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-121">Specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="79c49-122">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-122">The default value is false.</span></span></param>
        <param name="allowSelfSignedServerCert"><span data-ttu-id="79c49-123">サーバーからの自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-123">Specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="79c49-124">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-124">The default value is false.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="79c49-125">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="79c49-125">The encrypted credential used for authentication.</span></span> <span data-ttu-id="79c49-126">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="79c49-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="79c49-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="79c49-127">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="79c49-128">HBaseLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="79c49-128">Initializes a new instance of the HBaseLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AllowHostNameCNMismatch" />
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
            <span data-ttu-id="79c49-129">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように CA から発行される SSL 証明書名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-129">Gets or sets specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="79c49-130">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-130">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AllowSelfSignedServerCert" />
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
            <span data-ttu-id="79c49-131">取得または設定は、サーバーから自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-131">Gets or sets specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="79c49-132">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-132">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.AuthenticationType" />
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
            <span data-ttu-id="79c49-133">取得または HBase サーバーへの接続に使用する認証メカニズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-133">Gets or sets the authentication mechanism to use to connect to the HBase server.</span></span> <span data-ttu-id="79c49-134">使用可能な値が含まれます 'Anonymous'、'Basic'。</span><span class="sxs-lookup"><span data-stu-id="79c49-134">Possible values include: 'Anonymous', 'Basic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.EnableSsl" />
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
            <span data-ttu-id="79c49-135">取得または設定は、SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-135">Gets or sets specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="79c49-136">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="79c49-136">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="79c49-137">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-137">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="79c49-138">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="79c49-138">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="79c49-139">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="79c49-139">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Host" />
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
            <span data-ttu-id="79c49-140">取得または HBase サーバーの IP アドレスまたはホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-140">Gets or sets the IP address or host name of the HBase server.</span></span> <span data-ttu-id="79c49-141">(例: 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="79c49-141">(i.e. 192.168.222.160)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.HttpPath" />
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
            <span data-ttu-id="79c49-142">取得または HBase サーバーに対応する部分的な URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-142">Gets or sets the partial URL corresponding to the HBase server.</span></span>
            <span data-ttu-id="79c49-143">(/gateway/sandbox/hbase/version など)</span><span class="sxs-lookup"><span data-stu-id="79c49-143">(i.e. /gateway/sandbox/hbase/version)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Password" />
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
            <span data-ttu-id="79c49-144">取得またはユーザー名に対応するパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-144">Gets or sets the password corresponding to the user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Port" />
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
            <span data-ttu-id="79c49-145">取得または HBase インスタンスを使用してクライアント接続をリッスンする TCP ポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-145">Gets or sets the TCP port that the HBase instance uses to listen for client connections.</span></span> <span data-ttu-id="79c49-146">既定値は 9090 です。</span><span class="sxs-lookup"><span data-stu-id="79c49-146">The default value is 9090.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.TrustedCertPath" />
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
            <span data-ttu-id="79c49-147">取得または SSL 経由で接続するときに、サーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-147">Gets or sets the full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span>
            <span data-ttu-id="79c49-148">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="79c49-148">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="79c49-149">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="79c49-149">The default value is the cacerts.pem file installed with the IR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Username" />
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
            <span data-ttu-id="79c49-150">取得または HBase インスタンスへの接続に使用するユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="79c49-150">Gets or sets the user name used to connect to the HBase instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HBaseLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hBaseLinkedService.Validate " />
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
            <span data-ttu-id="79c49-151">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="79c49-151">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="79c49-152">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="79c49-152">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>