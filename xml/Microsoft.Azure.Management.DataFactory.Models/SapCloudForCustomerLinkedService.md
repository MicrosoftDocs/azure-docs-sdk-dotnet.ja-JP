<Type Name="SapCloudForCustomerLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService">
  <TypeSignature Language="C#" Value="public class SapCloudForCustomerLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SapCloudForCustomerLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SapCloudForCustomerLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SapCloudForCustomerLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("SapCloudForCustomer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="05ce8-101">顧客の SAP クラウドのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="05ce8-101">Linked service for SAP Cloud for Customer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05ce8-102">SapCloudForCustomerLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-102">Initializes a new instance of the SapCloudForCustomerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerLinkedService (object url, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional username As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService (url, additionalProperties, connectVia, description, username, password, encryptedCredential)" />
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
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="05ce8-103">顧客の OData API 用クラウドの SAP の URL です。</span><span class="sxs-lookup"><span data-stu-id="05ce8-103">The URL of SAP Cloud for Customer OData API.</span></span> <span data-ttu-id="05ce8-104">たとえば、'[https://[tenantname].crm.ondemand.com/sap/c4c/odata/v1]'。</span><span class="sxs-lookup"><span data-stu-id="05ce8-104">For example, '[https://[tenantname].crm.ondemand.com/sap/c4c/odata/v1]'.</span></span> <span data-ttu-id="05ce8-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="05ce8-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="05ce8-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="05ce8-107">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="05ce8-107">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="05ce8-108">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="05ce8-108">Linked service description.</span></span></param>
        <param name="username"><span data-ttu-id="05ce8-109">基本認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="05ce8-109">The username for Basic authentication.</span></span> <span data-ttu-id="05ce8-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="05ce8-111">基本認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="05ce8-111">The password for Basic authentication.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="05ce8-112">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-112">The encrypted credential used for authentication.</span></span> <span data-ttu-id="05ce8-113">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="05ce8-113">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="05ce8-114">EncryptedCredential またはユーザー名/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="05ce8-114">Either encryptedCredential or username/password must be provided.</span></span> <span data-ttu-id="05ce8-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-115">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="05ce8-116">SapCloudForCustomerLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-116">Initializes a new instance of the SapCloudForCustomerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="05ce8-117">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-117">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="05ce8-118">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="05ce8-118">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="05ce8-119">EncryptedCredential またはユーザー名/パスワードのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="05ce8-119">Either encryptedCredential or username/password must be provided.</span></span> <span data-ttu-id="05ce8-120">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-120">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Password" />
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
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05ce8-121">取得または基本認証のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-121">Gets or sets the password for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public object Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As Object" />
      <MemberSignature Language="F#" Value="member this.Url : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
            <span data-ttu-id="05ce8-122">取得または顧客 OData API の SAP クラウドの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-122">Gets or sets the URL of SAP Cloud for Customer OData API.</span></span> <span data-ttu-id="05ce8-123">たとえば、'[https://[tenantname].crm.ondemand.com/sap/c4c/odata/v1]'。</span><span class="sxs-lookup"><span data-stu-id="05ce8-123">For example, '[https://[tenantname].crm.ondemand.com/sap/c4c/odata/v1]'.</span></span> <span data-ttu-id="05ce8-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Username" />
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
            <span data-ttu-id="05ce8-125">取得または基本認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-125">Gets or sets the username for Basic authentication.</span></span> <span data-ttu-id="05ce8-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="05ce8-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sapCloudForCustomerLinkedService.Validate " />
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
            <span data-ttu-id="05ce8-127">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="05ce8-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="05ce8-128">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="05ce8-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>