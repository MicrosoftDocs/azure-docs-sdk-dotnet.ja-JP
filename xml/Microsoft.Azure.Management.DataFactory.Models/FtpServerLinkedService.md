<Type Name="FtpServerLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService">
  <TypeSignature Language="C#" Value="public class FtpServerLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FtpServerLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class FtpServerLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type FtpServerLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("FtpServer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e41bd-101">FTP サーバーでリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="e41bd-101">A FTP server Linked Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FtpServerLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.#ctor" />
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
            <span data-ttu-id="e41bd-102">FtpServerLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-102">Initializes a new instance of the FtpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FtpServerLinkedService (object host, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, string authenticationType = null, object userName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null, object enableSsl = null, object enableServerCertificateValidation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, string authenticationType, object userName, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential, object enableSsl, object enableServerCertificateValidation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional authenticationType As String = null, Optional userName As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null, Optional enableSsl As Object = null, Optional enableServerCertificateValidation As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService (host, additionalProperties, connectVia, description, port, authenticationType, userName, password, encryptedCredential, enableSsl, enableServerCertificateValidation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="userName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="enableServerCertificateValidation" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="e41bd-103">FTP サーバーのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-103">Host name of the FTP server.</span></span> <span data-ttu-id="e41bd-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="e41bd-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="e41bd-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="e41bd-106">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="e41bd-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="e41bd-107">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="e41bd-107">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="e41bd-108">クライアント接続をリッスンするように FTP サーバーが使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="e41bd-108">The TCP port number that the FTP server uses to listen for client connections.</span></span> <span data-ttu-id="e41bd-109">既定値は 21 です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-109">Default value is 21.</span></span> <span data-ttu-id="e41bd-110">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="e41bd-110">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="e41bd-111">FTP サーバーへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="e41bd-111">The authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="e41bd-112">使用可能な値が含まれます: 'Basic'、'Anonymous'</span><span class="sxs-lookup"><span data-stu-id="e41bd-112">Possible values include: 'Basic', 'Anonymous'</span></span></param>
        <param name="userName"><span data-ttu-id="e41bd-113">FTP サーバーにログオンするユーザー名。</span><span class="sxs-lookup"><span data-stu-id="e41bd-113">Username to logon the FTP server.</span></span> <span data-ttu-id="e41bd-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="e41bd-115">FTP サーバーにログオンするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="e41bd-115">Password to logon the FTP server.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="e41bd-116">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-116">The encrypted credential used for authentication.</span></span> <span data-ttu-id="e41bd-117">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="e41bd-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="e41bd-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="enableSsl"><span data-ttu-id="e41bd-119">True の場合は、SSL や TLS チャネル経由で FTP サーバーに接続します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-119">If true, connect to the FTP server over SSL/TLS channel.</span></span> <span data-ttu-id="e41bd-120">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-120">Default value is true.</span></span> <span data-ttu-id="e41bd-121">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-121">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="enableServerCertificateValidation"><span data-ttu-id="e41bd-122">True の場合、FTP サーバーの SSL 証明書の検証と SSL や TLS チャネル経由で接続します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-122">If true, validate the FTP server SSL certificate when connect over SSL/TLS channel.</span></span>
            <span data-ttu-id="e41bd-123">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-123">Default value is true.</span></span> <span data-ttu-id="e41bd-124">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-124">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="e41bd-125">FtpServerLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-125">Initializes a new instance of the FtpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.AuthenticationType" />
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
            <span data-ttu-id="e41bd-126">取得または FTP サーバーへの接続に使用する認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-126">Gets or sets the authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="e41bd-127">使用可能な値が含まれます: 'Basic'、'Anonymous'</span><span class="sxs-lookup"><span data-stu-id="e41bd-127">Possible values include: 'Basic', 'Anonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableServerCertificateValidation">
      <MemberSignature Language="C#" Value="public object EnableServerCertificateValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableServerCertificateValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableServerCertificateValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableServerCertificateValidation As Object" />
      <MemberSignature Language="F#" Value="member this.EnableServerCertificateValidation : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableServerCertificateValidation" />
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
            <span data-ttu-id="e41bd-128">取得または設定が true の場合、FTP サーバーの SSL 証明書の検証と SSL や TLS チャネル経由で接続します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-128">Gets or sets if true, validate the FTP server SSL certificate when connect over SSL/TLS channel.</span></span> <span data-ttu-id="e41bd-129">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-129">Default value is true.</span></span> <span data-ttu-id="e41bd-130">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-130">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableSsl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="e41bd-131">取得または設定が true の場合は、SSL や TLS チャネル経由で FTP サーバーに接続します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-131">Gets or sets if true, connect to the FTP server over SSL/TLS channel.</span></span> <span data-ttu-id="e41bd-132">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-132">Default value is true.</span></span> <span data-ttu-id="e41bd-133">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-133">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="e41bd-134">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-134">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="e41bd-135">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="e41bd-135">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="e41bd-136">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-136">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="e41bd-137">取得または FTP サーバーのホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-137">Gets or sets host name of the FTP server.</span></span> <span data-ttu-id="e41bd-138">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Password" />
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
            <span data-ttu-id="e41bd-139">取得または FTP サーバーにログオンするためのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-139">Gets or sets password to logon the FTP server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="e41bd-140">取得または FTP サーバーがクライアント接続をリッスンするように使用する TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-140">Gets or sets the TCP port number that the FTP server uses to listen for client connections.</span></span> <span data-ttu-id="e41bd-141">既定値は 21 です。</span><span class="sxs-lookup"><span data-stu-id="e41bd-141">Default value is 21.</span></span> <span data-ttu-id="e41bd-142">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="e41bd-142">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public object UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As Object" />
      <MemberSignature Language="F#" Value="member this.UserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.UserName" />
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
            <span data-ttu-id="e41bd-143">取得または FTP サーバーにログオンするユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-143">Gets or sets username to logon the FTP server.</span></span> <span data-ttu-id="e41bd-144">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="e41bd-144">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="ftpServerLinkedService.Validate " />
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
            <span data-ttu-id="e41bd-145">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e41bd-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e41bd-146">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e41bd-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>