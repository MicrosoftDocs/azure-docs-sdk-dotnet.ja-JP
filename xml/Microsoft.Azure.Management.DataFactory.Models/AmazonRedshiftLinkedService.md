<Type Name="AmazonRedshiftLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService">
  <TypeSignature Language="C#" Value="public class AmazonRedshiftLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonRedshiftLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonRedshiftLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AmazonRedshiftLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AmazonRedshift")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="44649-101">Amazon Redshift リンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="44649-101">Linked service for Amazon Redshift.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.#ctor" />
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
            <span data-ttu-id="44649-102">AmazonRedshiftLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44649-102">Initializes a new instance of the AmazonRedshiftLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftLinkedService (object server, object database, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object port = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object server, object database, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object port, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As Object, database As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional username As Object = null, Optional password As SecureString = null, Optional port As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService (server, database, additionalProperties, connectVia, description, username, password, port, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.Object" />
        <Parameter Name="database" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="44649-103">Amazon Redshift サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="44649-103">The name of the Amazon Redshift server.</span></span> <span data-ttu-id="44649-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="database"><span data-ttu-id="44649-105">Amazon Redshift ソースのデータベース名。</span><span class="sxs-lookup"><span data-stu-id="44649-105">The database name of the Amazon Redshift source.</span></span> <span data-ttu-id="44649-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="44649-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="44649-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="44649-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="44649-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="44649-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="44649-109">Linked service description.</span></span></param>
        <param name="username"><span data-ttu-id="44649-110">Amazon Redshift ソースのユーザー名。</span><span class="sxs-lookup"><span data-stu-id="44649-110">The username of the Amazon Redshift source.</span></span>
            <span data-ttu-id="44649-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="44649-112">Amazon Redshift ソースのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="44649-112">The password of the Amazon Redshift source.</span></span></param>
        <param name="port"><span data-ttu-id="44649-113">Amazon Redshift サーバーがクライアント接続をリッスンするように使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="44649-113">The TCP port number that the Amazon Redshift server uses to listen for client connections.</span></span> <span data-ttu-id="44649-114">既定値は</span><span class="sxs-lookup"><span data-stu-id="44649-114">The default value is</span></span>
            5439. <span data-ttu-id="44649-115">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="44649-115">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="44649-116">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="44649-116">The encrypted credential used for authentication.</span></span> <span data-ttu-id="44649-117">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="44649-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="44649-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-118">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="44649-119">AmazonRedshiftLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44649-119">Initializes a new instance of the AmazonRedshiftLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public object Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As Object" />
      <MemberSignature Language="F#" Value="member this.Database : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.database")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44649-120">取得または Amazon Redshift ソースのデータベース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-120">Gets or sets the database name of the Amazon Redshift source.</span></span> <span data-ttu-id="44649-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="44649-122">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-122">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="44649-123">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="44649-123">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="44649-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Password" />
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
            <span data-ttu-id="44649-125">取得または Amazon Redshift ソースのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-125">Gets or sets the password of the Amazon Redshift source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Port" />
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
            <span data-ttu-id="44649-126">取得または Amazon Redshift サーバーがクライアント接続をリッスンするように使用する TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-126">Gets or sets the TCP port number that the Amazon Redshift server uses to listen for client connections.</span></span> <span data-ttu-id="44649-127">既定値は、5439 です。</span><span class="sxs-lookup"><span data-stu-id="44649-127">The default value is 5439.</span></span>
            <span data-ttu-id="44649-128">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="44649-128">Type: integer (or Expression with resultType integer).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public object Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As Object" />
      <MemberSignature Language="F#" Value="member this.Server : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Server" />
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
            <span data-ttu-id="44649-129">取得または Amazon Redshift サーバーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-129">Gets or sets the name of the Amazon Redshift server.</span></span> <span data-ttu-id="44649-130">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-130">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="44649-131">取得または Amazon Redshift ソースのユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="44649-131">Gets or sets the username of the Amazon Redshift source.</span></span> <span data-ttu-id="44649-132">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="44649-132">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="amazonRedshiftLinkedService.Validate " />
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
            <span data-ttu-id="44649-133">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="44649-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="44649-134">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="44649-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>