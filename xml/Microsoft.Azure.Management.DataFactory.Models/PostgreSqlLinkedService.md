<Type Name="PostgreSqlLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService">
  <TypeSignature Language="C#" Value="public class PostgreSqlLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PostgreSqlLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class PostgreSqlLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type PostgreSqlLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("PostgreSql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c701e-101">PostgreSQL データ ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="c701e-101">Linked service for PostgreSQL data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PostgreSqlLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.#ctor" />
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
            <span data-ttu-id="c701e-102">PostgreSqlLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c701e-102">Initializes a new instance of the PostgreSqlLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PostgreSqlLinkedService (object server, object database, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object schema = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object server, object database, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object schema, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As Object, database As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional schema As Object = null, Optional username As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService (server, database, additionalProperties, connectVia, description, schema, username, password, encryptedCredential)" />
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
        <Parameter Name="schema" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="c701e-103">接続のサーバー名。</span><span class="sxs-lookup"><span data-stu-id="c701e-103">Server name for connection.</span></span> <span data-ttu-id="c701e-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="database"><span data-ttu-id="c701e-105">接続のデータベース名。</span><span class="sxs-lookup"><span data-stu-id="c701e-105">Database name for connection.</span></span> <span data-ttu-id="c701e-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="c701e-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="c701e-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="c701e-108">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="c701e-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="c701e-109">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="c701e-109">Linked service description.</span></span></param>
        <param name="schema"><span data-ttu-id="c701e-110">接続のスキーマ名。</span><span class="sxs-lookup"><span data-stu-id="c701e-110">Schema name for connection.</span></span> <span data-ttu-id="c701e-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="username"><span data-ttu-id="c701e-112">認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="c701e-112">Username for authentication.</span></span> <span data-ttu-id="c701e-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="c701e-114">認証のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="c701e-114">Password for authentication.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="c701e-115">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="c701e-115">The encrypted credential used for authentication.</span></span> <span data-ttu-id="c701e-116">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="c701e-116">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="c701e-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-117">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="c701e-118">PostgreSqlLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c701e-118">Initializes a new instance of the PostgreSqlLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public object Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As Object" />
      <MemberSignature Language="F#" Value="member this.Database : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Database" />
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
            <span data-ttu-id="c701e-119">取得または接続のデータベース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-119">Gets or sets database name for connection.</span></span> <span data-ttu-id="c701e-120">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-120">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="c701e-121">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-121">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="c701e-122">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="c701e-122">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="c701e-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Password" />
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
            <span data-ttu-id="c701e-124">取得または認証用のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-124">Gets or sets password for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public object Schema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Schema" />
      <MemberSignature Language="VB.NET" Value="Public Property Schema As Object" />
      <MemberSignature Language="F#" Value="member this.Schema : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c701e-125">取得または接続のスキーマ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-125">Gets or sets schema name for connection.</span></span> <span data-ttu-id="c701e-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public object Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As Object" />
      <MemberSignature Language="F#" Value="member this.Server : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Server" />
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
            <span data-ttu-id="c701e-127">取得または接続のサーバー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-127">Gets or sets server name for connection.</span></span> <span data-ttu-id="c701e-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Username" />
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
            <span data-ttu-id="c701e-129">取得または認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c701e-129">Gets or sets username for authentication.</span></span> <span data-ttu-id="c701e-130">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c701e-130">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PostgreSqlLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="postgreSqlLinkedService.Validate " />
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
            <span data-ttu-id="c701e-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c701e-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c701e-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c701e-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>