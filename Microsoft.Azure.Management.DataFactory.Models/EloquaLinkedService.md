<Type Name="EloquaLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService">
  <TypeSignature Language="C#" Value="public class EloquaLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EloquaLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class EloquaLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type EloquaLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Eloqua")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="241e7-101">Eloqua サーバーにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-101">Eloqua server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EloquaLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="241e7-102">EloquaLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="241e7-102">Initializes a new instance of the EloquaLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EloquaLinkedService (object endpoint, object username, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object endpoint, object username, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Object, username As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional password As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService (endpoint, username, additionalProperties, connectVia, description, password, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Object" />
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
        <param name="endpoint"><span data-ttu-id="241e7-103">Eloqua サーバーのエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="241e7-103">The endpoint of the Eloqua server.</span></span> <span data-ttu-id="241e7-104">(つまり eloqua.example.com)</span><span class="sxs-lookup"><span data-stu-id="241e7-104">(i.e. eloqua.example.com)</span></span></param>
        <param name="username"><span data-ttu-id="241e7-105">サイト名と形式で Eloqua アカウントのユーザー名: sitename/ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="241e7-105">The site name and user name of your Eloqua account in the form: sitename/username.</span></span> <span data-ttu-id="241e7-106">(つまり Eloqua/Alice)</span><span class="sxs-lookup"><span data-stu-id="241e7-106">(i.e. Eloqua/Alice)</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="241e7-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="241e7-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="241e7-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="241e7-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="241e7-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="241e7-109">Linked service description.</span></span></param>
        <param name="password"><span data-ttu-id="241e7-110">ユーザー名に対応するパスワード。</span><span class="sxs-lookup"><span data-stu-id="241e7-110">The password corresponding to the user name.</span></span></param>
        <param name="useEncryptedEndpoints"><span data-ttu-id="241e7-111">データ ソースのエンドポイントが HTTPS を使用して暗号化されるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-111">Specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="241e7-112">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-112">The default value is true.</span></span></param>
        <param name="useHostVerification"><span data-ttu-id="241e7-113">SSL 経由で接続するときに、サーバーの証明書内のホスト名がサーバーのホスト名と一致する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-113">Specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="241e7-114">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-114">The default value is true.</span></span></param>
        <param name="usePeerVerification"><span data-ttu-id="241e7-115">SSL 経由で接続するときに、サーバーの ID を検証するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-115">Specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="241e7-116">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-116">The default value is true.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="241e7-117">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="241e7-117">The encrypted credential used for authentication.</span></span> <span data-ttu-id="241e7-118">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="241e7-118">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="241e7-119">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="241e7-119">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="241e7-120">EloquaLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="241e7-120">Initializes a new instance of the EloquaLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="241e7-121">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-121">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="241e7-122">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="241e7-122">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="241e7-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="241e7-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public object Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Object" />
      <MemberSignature Language="F#" Value="member this.Endpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="241e7-124">取得または Eloqua サーバーのエンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-124">Gets or sets the endpoint of the Eloqua server.</span></span> <span data-ttu-id="241e7-125">(つまり eloqua.example.com)</span><span class="sxs-lookup"><span data-stu-id="241e7-125">(i.e. eloqua.example.com)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Password" />
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
            <span data-ttu-id="241e7-126">取得またはユーザー名に対応するパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-126">Gets or sets the password corresponding to the user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UseEncryptedEndpoints" />
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
            <span data-ttu-id="241e7-127">取得または設定は、データ ソースのエンドポイントは HTTPS を使用して暗号化するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-127">Gets or sets specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="241e7-128">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-128">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UseHostVerification" />
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
            <span data-ttu-id="241e7-129">取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように、サーバーの証明書内のホスト名を必要とするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-129">Gets or sets specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="241e7-130">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-130">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.UsePeerVerification" />
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
            <span data-ttu-id="241e7-131">取得または設定は、SSL 経由で接続するときに、サーバーの id を確認するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="241e7-131">Gets or sets specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="241e7-132">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="241e7-132">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Username" />
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
            <span data-ttu-id="241e7-133">取得またはフォームで Eloqua アカウントのユーザー名とサイトの名前を設定します。 サイト名/ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="241e7-133">Gets or sets the site name and user name of your Eloqua account in the form: sitename/username.</span></span> <span data-ttu-id="241e7-134">(つまり Eloqua/Alice)</span><span class="sxs-lookup"><span data-stu-id="241e7-134">(i.e. Eloqua/Alice)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.EloquaLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="eloquaLinkedService.Validate " />
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
            <span data-ttu-id="241e7-135">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="241e7-135">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="241e7-136">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="241e7-136">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>