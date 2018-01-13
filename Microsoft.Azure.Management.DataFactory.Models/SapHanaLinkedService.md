<Type Name="SapHanaLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService">
  <TypeSignature Language="C#" Value="public class SapHanaLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SapHanaLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SapHanaLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SapHanaLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("SapHana")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="53b2a-101">SAP HANA にリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-101">SAP HANA Linked Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapHanaLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.#ctor" />
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
            <span data-ttu-id="53b2a-102">SapHanaLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-102">Initializes a new instance of the SapHanaLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapHanaLinkedService (object server, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string authenticationType = null, object userName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object server, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string authenticationType, object userName, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional authenticationType As String = null, Optional userName As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService (server, additionalProperties, connectVia, description, authenticationType, userName, password, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="userName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="53b2a-103">SAP HANA サーバーのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="53b2a-103">Host name of the SAP HANA server.</span></span> <span data-ttu-id="53b2a-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="53b2a-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="53b2a-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="53b2a-106">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="53b2a-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="53b2a-107">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="53b2a-107">Linked service description.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="53b2a-108">SAP HANA サーバーへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="53b2a-108">The authentication type to be used to connect to the SAP HANA server.</span></span> <span data-ttu-id="53b2a-109">使用可能な値が含まれます: 'Basic'、'Windows'</span><span class="sxs-lookup"><span data-stu-id="53b2a-109">Possible values include: 'Basic', 'Windows'</span></span></param>
        <param name="userName"><span data-ttu-id="53b2a-110">SAP HANA サーバーにアクセスするユーザー名。</span><span class="sxs-lookup"><span data-stu-id="53b2a-110">Username to access the SAP HANA server.</span></span>
            <span data-ttu-id="53b2a-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="53b2a-112">SAP HANA サーバーにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="53b2a-112">Password to access the SAP HANA server.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="53b2a-113">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-113">The encrypted credential used for authentication.</span></span> <span data-ttu-id="53b2a-114">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="53b2a-114">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="53b2a-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-115">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="53b2a-116">SapHanaLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-116">Initializes a new instance of the SapHanaLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.AuthenticationType" />
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
            <span data-ttu-id="53b2a-117">取得または SAP HANA サーバーへの接続に使用する認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-117">Gets or sets the authentication type to be used to connect to the SAP HANA server.</span></span> <span data-ttu-id="53b2a-118">使用可能な値が含まれます: 'Basic'、'Windows'</span><span class="sxs-lookup"><span data-stu-id="53b2a-118">Possible values include: 'Basic', 'Windows'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="53b2a-119">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-119">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="53b2a-120">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="53b2a-120">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="53b2a-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.Password" />
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
            <span data-ttu-id="53b2a-122">取得または SAP HANA サーバーにアクセスするためのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-122">Gets or sets password to access the SAP HANA server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public object Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As Object" />
      <MemberSignature Language="F#" Value="member this.Server : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.Server" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.server")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53b2a-123">取得または SAP HANA サーバーのホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-123">Gets or sets host name of the SAP HANA server.</span></span> <span data-ttu-id="53b2a-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public object UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As Object" />
      <MemberSignature Language="F#" Value="member this.UserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.UserName" />
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
            <span data-ttu-id="53b2a-125">取得または SAP HANA サーバーにアクセスするユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-125">Gets or sets username to access the SAP HANA server.</span></span> <span data-ttu-id="53b2a-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="53b2a-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapHanaLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sapHanaLinkedService.Validate " />
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
            <span data-ttu-id="53b2a-127">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="53b2a-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="53b2a-128">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="53b2a-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>