<Type Name="PrestoLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService">
  <TypeSignature Language="C#" Value="public class PrestoLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PrestoLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class PrestoLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type PrestoLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Presto")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="57a57-101">Presto サーバーにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-101">Presto server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrestoLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57a57-102">PrestoLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57a57-102">Initializes a new instance of the PrestoLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrestoLinkedService (object host, object serverVersion, object catalog, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object timeZoneID = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, object serverVersion, object catalog, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object timeZoneID, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.#ctor(System.Object,System.Object,System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, serverVersion As Object, catalog As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional username As Object = null, Optional password As SecretBase = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional timeZoneID As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService : obj * obj * obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService (host, serverVersion, catalog, authenticationType, additionalProperties, connectVia, description, port, username, password, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, timeZoneID, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="serverVersion" Type="System.Object" />
        <Parameter Name="catalog" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="timeZoneID" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="57a57-103">Presto サーバーの IP アドレスまたはホスト名。</span><span class="sxs-lookup"><span data-stu-id="57a57-103">The IP address or host name of the Presto server.</span></span> <span data-ttu-id="57a57-104">(例: 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="57a57-104">(i.e. 192.168.222.160)</span></span></param>
        <param name="serverVersion"><span data-ttu-id="57a57-105">Presto サーバーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="57a57-105">The version of the Presto server.</span></span> <span data-ttu-id="57a57-106">(例: 0.148-t)</span><span class="sxs-lookup"><span data-stu-id="57a57-106">(i.e. 0.148-t)</span></span></param>
        <param name="catalog"><span data-ttu-id="57a57-107">サーバーに対するすべての要求のカタログ コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="57a57-107">The catalog context for all request against the server.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="57a57-108">Presto サーバーへの接続に使用する認証メカニズム。</span><span class="sxs-lookup"><span data-stu-id="57a57-108">The authentication mechanism used to connect to the Presto server.</span></span> <span data-ttu-id="57a57-109">使用可能な値が含まれます 'Anonymous'、'LDAP'。</span><span class="sxs-lookup"><span data-stu-id="57a57-109">Possible values include: 'Anonymous', 'LDAP'</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="57a57-110">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="57a57-110">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="57a57-111">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="57a57-111">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="57a57-112">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="57a57-112">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="57a57-113">Presto サーバーがクライアント接続のリッスンに使用する TCP ポート。</span><span class="sxs-lookup"><span data-stu-id="57a57-113">The TCP port that the Presto server uses to listen for client connections.</span></span> <span data-ttu-id="57a57-114">既定値は 8080 です。</span><span class="sxs-lookup"><span data-stu-id="57a57-114">The default value is 8080.</span></span></param>
        <param name="username"><span data-ttu-id="57a57-115">Presto サーバーへの接続に使用されるユーザー名。</span><span class="sxs-lookup"><span data-stu-id="57a57-115">The user name used to connect to the Presto server.</span></span></param>
        <param name="password"><span data-ttu-id="57a57-116">ユーザー名に対応するパスワード。</span><span class="sxs-lookup"><span data-stu-id="57a57-116">The password corresponding to the user name.</span></span></param>
        <param name="enableSsl"><span data-ttu-id="57a57-117">SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-117">Specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="57a57-118">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-118">The default value is false.</span></span></param>
        <param name="trustedCertPath"><span data-ttu-id="57a57-119">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。</span><span class="sxs-lookup"><span data-stu-id="57a57-119">The full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span> <span data-ttu-id="57a57-120">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="57a57-120">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="57a57-121">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="57a57-121">The default value is the cacerts.pem file installed with the IR.</span></span></param>
        <param name="useSystemTrustStore"><span data-ttu-id="57a57-122">システムの信頼ストアと指定した PEM ファイルのどちらの CA 証明書を使用するかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-122">Specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="57a57-123">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-123">The default value is false.</span></span></param>
        <param name="allowHostNameCNMismatch"><span data-ttu-id="57a57-124">SSL 経由で接続するときに、CA が発行した SSL 証明書名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-124">Specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="57a57-125">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-125">The default value is false.</span></span></param>
        <param name="allowSelfSignedServerCert"><span data-ttu-id="57a57-126">サーバーからの自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-126">Specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="57a57-127">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-127">The default value is false.</span></span></param>
        <param name="timeZoneID"><span data-ttu-id="57a57-128">接続で使用されるローカルのタイム ゾーン。</span><span class="sxs-lookup"><span data-stu-id="57a57-128">The local time zone used by the connection.</span></span> <span data-ttu-id="57a57-129">このオプションの有効な値は、IANA タイム ゾーン データベースで指定されます。</span><span class="sxs-lookup"><span data-stu-id="57a57-129">Valid values for this option are specified in the IANA Time Zone Database.</span></span> <span data-ttu-id="57a57-130">既定値は、システムのタイム ゾーンです。</span><span class="sxs-lookup"><span data-stu-id="57a57-130">The default value is the system time zone.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="57a57-131">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="57a57-131">The encrypted credential used for authentication.</span></span> <span data-ttu-id="57a57-132">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="57a57-132">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="57a57-133">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="57a57-133">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="57a57-134">PrestoLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57a57-134">Initializes a new instance of the PrestoLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AllowHostNameCNMismatch" />
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
            <span data-ttu-id="57a57-135">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように CA から発行される SSL 証明書名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-135">Gets or sets specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="57a57-136">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-136">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AllowSelfSignedServerCert" />
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
            <span data-ttu-id="57a57-137">取得または設定は、サーバーから自己署名証明書を許可するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-137">Gets or sets specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="57a57-138">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-138">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.AuthenticationType" />
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
            <span data-ttu-id="57a57-139">取得または Presto サーバーへの接続に使用される認証方式を設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-139">Gets or sets the authentication mechanism used to connect to the Presto server.</span></span> <span data-ttu-id="57a57-140">使用可能な値が含まれます 'Anonymous'、'LDAP'。</span><span class="sxs-lookup"><span data-stu-id="57a57-140">Possible values include: 'Anonymous', 'LDAP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Catalog">
      <MemberSignature Language="C#" Value="public object Catalog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Catalog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Catalog" />
      <MemberSignature Language="VB.NET" Value="Public Property Catalog As Object" />
      <MemberSignature Language="F#" Value="member this.Catalog : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Catalog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.catalog")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57a57-141">取得またはサーバーに対するすべての要求に対してカタログのコンテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-141">Gets or sets the catalog context for all request against the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.EnableSsl" />
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
            <span data-ttu-id="57a57-142">取得または設定は、SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-142">Gets or sets specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="57a57-143">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-143">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="57a57-144">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-144">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="57a57-145">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="57a57-145">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="57a57-146">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="57a57-146">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Host" />
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
            <span data-ttu-id="57a57-147">取得または Presto のサーバーの IP アドレスまたはホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-147">Gets or sets the IP address or host name of the Presto server.</span></span>
            <span data-ttu-id="57a57-148">(例: 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="57a57-148">(i.e. 192.168.222.160)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Password" />
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
            <span data-ttu-id="57a57-149">取得またはユーザー名に対応するパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-149">Gets or sets the password corresponding to the user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Port" />
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
            <span data-ttu-id="57a57-150">取得または Presto サーバーがクライアント接続のリッスンに使用される TCP ポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-150">Gets or sets the TCP port that the Presto server uses to listen for client connections.</span></span> <span data-ttu-id="57a57-151">既定値は 8080 です。</span><span class="sxs-lookup"><span data-stu-id="57a57-151">The default value is 8080.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerVersion">
      <MemberSignature Language="C#" Value="public object ServerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.ServerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerVersion As Object" />
      <MemberSignature Language="F#" Value="member this.ServerVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.ServerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serverVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57a57-152">取得または Presto server のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-152">Gets or sets the version of the Presto server.</span></span> <span data-ttu-id="57a57-153">(例: 0.148-t)</span><span class="sxs-lookup"><span data-stu-id="57a57-153">(i.e. 0.148-t)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZoneID">
      <MemberSignature Language="C#" Value="public object TimeZoneID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TimeZoneID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.TimeZoneID" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZoneID As Object" />
      <MemberSignature Language="F#" Value="member this.TimeZoneID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.TimeZoneID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.timeZoneID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57a57-154">取得または接続で使用されるローカル タイム ゾーンを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-154">Gets or sets the local time zone used by the connection.</span></span> <span data-ttu-id="57a57-155">このオプションの有効な値は、IANA タイム ゾーン データベースで指定されます。</span><span class="sxs-lookup"><span data-stu-id="57a57-155">Valid values for this option are specified in the IANA Time Zone Database.</span></span> <span data-ttu-id="57a57-156">既定値は、システムのタイム ゾーンです。</span><span class="sxs-lookup"><span data-stu-id="57a57-156">The default value is the system time zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.TrustedCertPath" />
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
            <span data-ttu-id="57a57-157">取得または SSL 経由で接続するときに、サーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-157">Gets or sets the full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span>
            <span data-ttu-id="57a57-158">このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="57a57-158">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="57a57-159">既定値は、IR でインストールされる cacerts.pem ファイルです。</span><span class="sxs-lookup"><span data-stu-id="57a57-159">The default value is the cacerts.pem file installed with the IR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Username" />
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
            <span data-ttu-id="57a57-160">取得または Presto サーバーへの接続に使用するユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-160">Gets or sets the user name used to connect to the Presto server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.UseSystemTrustStore" />
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
            <span data-ttu-id="57a57-161">取得または設定は、システムのトラスト ストアから、または指定した PEM ファイルから CA 証明書を使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="57a57-161">Gets or sets specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="57a57-162">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="57a57-162">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PrestoLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="prestoLinkedService.Validate " />
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
            <span data-ttu-id="57a57-163">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="57a57-163">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="57a57-164">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="57a57-164">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>