<Type Name="ApnsCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential">
  <TypeSignature Language="C#" Value="public class ApnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApnsCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class ApnsCredential" />
  <TypeSignature Language="F#" Value="type ApnsCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="eacda-101">NotificationHub ApnsCredential の説明です。</span><span class="sxs-lookup"><span data-stu-id="eacda-101">Description of a NotificationHub ApnsCredential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eacda-102">ApnsCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="eacda-102">Initializes a new instance of the ApnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApnsCredential (string apnsCertificate = null, string certificateKey = null, string endpoint = null, string thumbprint = null, string keyId = null, string appName = null, string appId = null, string token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string apnsCertificate, string certificateKey, string endpoint, string thumbprint, string keyId, string appName, string appId, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional apnsCertificate As String = null, Optional certificateKey As String = null, Optional endpoint As String = null, Optional thumbprint As String = null, Optional keyId As String = null, Optional appName As String = null, Optional appId As String = null, Optional token As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential (apnsCertificate, certificateKey, endpoint, thumbprint, keyId, appName, appId, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="apnsCertificate" Type="System.String" />
        <Parameter Name="certificateKey" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="keyId" Type="System.String" />
        <Parameter Name="appName" Type="System.String" />
        <Parameter Name="appId" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apnsCertificate"><span data-ttu-id="eacda-103">APNS 証明書。</span><span class="sxs-lookup"><span data-stu-id="eacda-103">The APNS certificate.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="eacda-104">証明書のキー。</span><span class="sxs-lookup"><span data-stu-id="eacda-104">The certificate key.</span></span></param>
        <param name="endpoint"><span data-ttu-id="eacda-105">この資格情報のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="eacda-105">The endpoint of this credential.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="eacda-106">Apns 証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="eacda-106">The Apns certificate Thumbprint</span></span></param>
        <param name="keyId"><span data-ttu-id="eacda-107">開発者アカウントから取得した、10 文字のキー識別子 (kid) キー</span><span class="sxs-lookup"><span data-stu-id="eacda-107">A 10-character key identifier (kid) key, obtained from your developer account</span></span></param>
        <param name="appName"><span data-ttu-id="eacda-108">アプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="eacda-108">The name of the application</span></span></param>
        <param name="appId"><span data-ttu-id="eacda-109">発行者 (iss) 登録済みのクレーム キー、値が、開発者アカウントから取得した、10 文字チーム ID</span><span class="sxs-lookup"><span data-stu-id="eacda-109">The issuer (iss) registered claim key, whose value is your 10-character Team ID, obtained from your developer account</span></span></param>
        <param name="token"><span data-ttu-id="eacda-110">プロバイダーの認証トークンを開発者アカウントから入手しました。</span><span class="sxs-lookup"><span data-stu-id="eacda-110">Provider Authentication Token, obtained through your developer account</span></span></param>
        <summary>
            <span data-ttu-id="eacda-111">ApnsCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="eacda-111">Initializes a new instance of the ApnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCertificate">
      <MemberSignature Language="C#" Value="public string ApnsCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApnsCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.ApnsCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCertificate As String" />
      <MemberSignature Language="F#" Value="member this.ApnsCertificate : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.ApnsCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apnsCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-112">取得または APNS 証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="eacda-112">Gets or sets the APNS certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppId">
      <MemberSignature Language="C#" Value="public string AppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.AppId" />
      <MemberSignature Language="VB.NET" Value="Public Property AppId As String" />
      <MemberSignature Language="F#" Value="member this.AppId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.AppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-113">取得または設定の値は、開発者アカウントから取得した、10 文字チーム ID、発行者 (iss) 登録済みのクレーム キー</span><span class="sxs-lookup"><span data-stu-id="eacda-113">Gets or sets the issuer (iss) registered claim key, whose value is your 10-character Team ID, obtained from your developer account</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppName">
      <MemberSignature Language="C#" Value="public string AppName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.AppName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppName As String" />
      <MemberSignature Language="F#" Value="member this.AppName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.AppName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-114">取得または設定、アプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="eacda-114">Gets or sets the name of the application</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateKey">
      <MemberSignature Language="C#" Value="public string CertificateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.CertificateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateKey As String" />
      <MemberSignature Language="F#" Value="member this.CertificateKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.CertificateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-115">取得または証明書のキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="eacda-115">Gets or sets the certificate key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-116">取得または、この資格情報のエンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="eacda-116">Gets or sets the endpoint of this credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyId">
      <MemberSignature Language="C#" Value="public string KeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.KeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyId As String" />
      <MemberSignature Language="F#" Value="member this.KeyId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.KeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-117">取得または設定 10 文字のキー識別子 (kid) キーでは、開発者アカウントから取得</span><span class="sxs-lookup"><span data-stu-id="eacda-117">Gets or sets a 10-character key identifier (kid) key, obtained from your developer account</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-118">取得または設定、Apns 証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="eacda-118">Gets or sets the Apns certificate Thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eacda-119">開発者アカウントから入手したプロバイダーの認証トークンを取得または設定</span><span class="sxs-lookup"><span data-stu-id="eacda-119">Gets or sets provider Authentication Token, obtained through your developer account</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>