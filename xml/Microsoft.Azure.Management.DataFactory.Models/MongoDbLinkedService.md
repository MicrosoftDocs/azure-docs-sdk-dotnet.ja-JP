<Type Name="MongoDbLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService">
  <TypeSignature Language="C#" Value="public class MongoDbLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MongoDbLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class MongoDbLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type MongoDbLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("MongoDb")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6eff1-101">MongoDb データ ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="6eff1-101">Linked service for MongoDb data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MongoDbLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.#ctor" />
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
            <span data-ttu-id="6eff1-102">MongoDbLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-102">Initializes a new instance of the MongoDbLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MongoDbLinkedService (object server, object databaseName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string authenticationType = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object authSource = null, object port = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object server, object databaseName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string authenticationType, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object authSource, object port, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As Object, databaseName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional authenticationType As String = null, Optional username As Object = null, Optional password As SecureString = null, Optional authSource As Object = null, Optional port As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService (server, databaseName, additionalProperties, connectVia, description, authenticationType, username, password, authSource, port, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.Object" />
        <Parameter Name="databaseName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="authSource" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="6eff1-103">MongoDB サーバーの IP アドレスまたはサーバー名。</span><span class="sxs-lookup"><span data-stu-id="6eff1-103">The IP address or server name of the MongoDB server.</span></span> <span data-ttu-id="6eff1-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="databaseName"><span data-ttu-id="6eff1-105">アクセスする MongoDB データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6eff1-105">The name of the MongoDB database that you want to access.</span></span> <span data-ttu-id="6eff1-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="6eff1-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="6eff1-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="6eff1-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="6eff1-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="6eff1-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="6eff1-109">Linked service description.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="6eff1-110">MongoDB データベースへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="6eff1-110">The authentication type to be used to connect to the MongoDB database.</span></span> <span data-ttu-id="6eff1-111">使用可能な値が含まれます: 'Basic'、'Anonymous'</span><span class="sxs-lookup"><span data-stu-id="6eff1-111">Possible values include: 'Basic', 'Anonymous'</span></span></param>
        <param name="username"><span data-ttu-id="6eff1-112">認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="6eff1-112">Username for authentication.</span></span> <span data-ttu-id="6eff1-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="6eff1-114">認証のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="6eff1-114">Password for authentication.</span></span></param>
        <param name="authSource"><span data-ttu-id="6eff1-115">ユーザー名とパスワードを確認するデータベースです。</span><span class="sxs-lookup"><span data-stu-id="6eff1-115">Database to verify the username and password.</span></span> <span data-ttu-id="6eff1-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="port"><span data-ttu-id="6eff1-117">MongoDB サーバーがクライアント接続をリッスンするように使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="6eff1-117">The TCP port number that the MongoDB server uses to listen for client connections.</span></span> <span data-ttu-id="6eff1-118">既定値は、27017 です。</span><span class="sxs-lookup"><span data-stu-id="6eff1-118">The default value is 27017.</span></span> <span data-ttu-id="6eff1-119">型: 整数 (または式と resultType 整数)、最小値。</span><span class="sxs-lookup"><span data-stu-id="6eff1-119">Type: integer (or Expression with resultType integer), minimum:</span></span>
            0.</param>
        <param name="encryptedCredential"><span data-ttu-id="6eff1-120">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-120">The encrypted credential used for authentication.</span></span> <span data-ttu-id="6eff1-121">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="6eff1-121">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="6eff1-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-122">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="6eff1-123">MongoDbLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-123">Initializes a new instance of the MongoDbLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.AuthenticationType" />
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
            <span data-ttu-id="6eff1-124">取得または MongoDB データベースへの接続に使用する認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-124">Gets or sets the authentication type to be used to connect to the MongoDB database.</span></span> <span data-ttu-id="6eff1-125">使用可能な値が含まれます: 'Basic'、'Anonymous'</span><span class="sxs-lookup"><span data-stu-id="6eff1-125">Possible values include: 'Basic', 'Anonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthSource">
      <MemberSignature Language="C#" Value="public object AuthSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AuthSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.AuthSource" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthSource As Object" />
      <MemberSignature Language="F#" Value="member this.AuthSource : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.AuthSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6eff1-126">取得またはユーザー名とパスワードを確認するデータベースを設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-126">Gets or sets database to verify the username and password.</span></span> <span data-ttu-id="6eff1-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public object DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As Object" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6eff1-128">取得または設定にアクセスする MongoDB データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6eff1-128">Gets or sets the name of the MongoDB database that you want to access.</span></span> <span data-ttu-id="6eff1-129">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-129">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="6eff1-130">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-130">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="6eff1-131">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="6eff1-131">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="6eff1-132">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-132">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Password" />
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
            <span data-ttu-id="6eff1-133">取得または認証用のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-133">Gets or sets password for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Port" />
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
            <span data-ttu-id="6eff1-134">取得または MongoDB サーバーがクライアント接続をリッスンするように使用する TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-134">Gets or sets the TCP port number that the MongoDB server uses to listen for client connections.</span></span> <span data-ttu-id="6eff1-135">既定値は、27017 です。</span><span class="sxs-lookup"><span data-stu-id="6eff1-135">The default value is 27017.</span></span> <span data-ttu-id="6eff1-136">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="6eff1-136">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public object Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As Object" />
      <MemberSignature Language="F#" Value="member this.Server : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Server" />
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
            <span data-ttu-id="6eff1-137">取得または MongoDB サーバーの IP アドレスまたはサーバー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-137">Gets or sets the IP address or server name of the MongoDB server.</span></span>
            <span data-ttu-id="6eff1-138">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Username" />
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
            <span data-ttu-id="6eff1-139">取得または認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-139">Gets or sets username for authentication.</span></span> <span data-ttu-id="6eff1-140">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="6eff1-140">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MongoDbLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="mongoDbLinkedService.Validate " />
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
            <span data-ttu-id="6eff1-141">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6eff1-141">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6eff1-142">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6eff1-142">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>