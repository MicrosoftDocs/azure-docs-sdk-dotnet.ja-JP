<Type Name="ConcurLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService">
  <TypeSignature Language="C#" Value="public class ConcurLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConcurLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class ConcurLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type ConcurLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Concur")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="08a5d-101">Concur のリンクされたサービスのサービスです。</span><span class="sxs-lookup"><span data-stu-id="08a5d-101">Concur Serivce linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConcurLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08a5d-102">ConcurLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-102">Initializes a new instance of the ConcurLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConcurLinkedService (object clientId, object username, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object clientId, object username, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As Object, username As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional password As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService (clientId, username, additionalProperties, connectVia, description, password, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="08a5d-103">Concur App Management によって提供されるアプリケーションの client_id。</span><span class="sxs-lookup"><span data-stu-id="08a5d-103">Application client_id supplied by Concur App Management.</span></span></param>
        <param name="username"><span data-ttu-id="08a5d-104">Concur サービスへのアクセスに使用するユーザー名。</span><span class="sxs-lookup"><span data-stu-id="08a5d-104">The user name that you use to access Concur Service.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="08a5d-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="08a5d-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="08a5d-106">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="08a5d-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="08a5d-107">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="08a5d-107">Linked service description.</span></span></param>
        <param name="password"><span data-ttu-id="08a5d-108">username フィールドに指定したユーザー名に対応するパスワード。</span><span class="sxs-lookup"><span data-stu-id="08a5d-108">The password corresponding to the user name that you provided in the username field.</span></span></param>
        <param name="useEncryptedEndpoints"><span data-ttu-id="08a5d-109">データ ソースのエンドポイントが HTTPS を使用して暗号化されるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-109">Specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="08a5d-110">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-110">The default value is true.</span></span></param>
        <param name="useHostVerification"><span data-ttu-id="08a5d-111">SSL 経由で接続するときに、サーバーの証明書内のホスト名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-111">Specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="08a5d-112">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-112">The default value is true.</span></span></param>
        <param name="usePeerVerification"><span data-ttu-id="08a5d-113">SSL 経由で接続するときに、サーバーの ID を検証するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-113">Specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="08a5d-114">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-114">The default value is true.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="08a5d-115">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-115">The encrypted credential used for authentication.</span></span> <span data-ttu-id="08a5d-116">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="08a5d-116">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="08a5d-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="08a5d-117">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="08a5d-118">ConcurLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-118">Initializes a new instance of the ConcurLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public object ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As Object" />
      <MemberSignature Language="F#" Value="member this.ClientId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08a5d-119">取得またはアプリの管理を Concur から提供されたアプリケーション client_id を設定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-119">Gets or sets application client_id supplied by Concur App Management.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="08a5d-120">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-120">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="08a5d-121">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="08a5d-121">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="08a5d-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="08a5d-122">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.Password" />
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
            <span data-ttu-id="08a5d-123">取得またはユーザー名 フィールドで指定したユーザー名に対応するパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-123">Gets or sets the password corresponding to the user name that you provided in the username field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UseEncryptedEndpoints" />
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
            <span data-ttu-id="08a5d-124">取得または設定は、データ ソースのエンドポイントは HTTPS を使用して暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-124">Gets or sets specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="08a5d-125">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-125">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UseHostVerification" />
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
            <span data-ttu-id="08a5d-126">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように、サーバーの証明書内のホスト名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-126">Gets or sets specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="08a5d-127">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-127">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.UsePeerVerification" />
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
            <span data-ttu-id="08a5d-128">取得または設定は、SSL 経由で接続するときに、サーバーの id を確認するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-128">Gets or sets specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="08a5d-129">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08a5d-129">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.Username" />
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
            <span data-ttu-id="08a5d-130">取得またはサービスの Concur へのアクセスに使用するユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-130">Gets or sets the user name that you use to access Concur Service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ConcurLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="concurLinkedService.Validate " />
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
            <span data-ttu-id="08a5d-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="08a5d-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="08a5d-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="08a5d-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>