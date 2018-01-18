<Type Name="ImportExtensionRequest" FullName="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest">
  <TypeSignature Language="C#" Value="public class ImportExtensionRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ImportExtensionRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ImportExtensionRequest" />
  <TypeSignature Language="F#" Value="type ImportExtensionRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="77efa-101">データベースのパラメーターをインポートします。</span><span class="sxs-lookup"><span data-stu-id="77efa-101">Import database parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportExtensionRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77efa-102">ImportExtensionRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77efa-102">Initializes a new instance of the ImportExtensionRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportExtensionRequest (Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.#ctor(Microsoft.Azure.Management.Sql.Models.StorageKeyType,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.AuthenticationType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest : Microsoft.Azure.Management.Sql.Models.StorageKeyType * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" Usage="new Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest (storageKeyType, storageKey, storageUri, administratorLogin, administratorLoginPassword, name, type, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageKeyType" Type="Microsoft.Azure.Management.Sql.Models.StorageKeyType" />
        <Parameter Name="storageKey" Type="System.String" />
        <Parameter Name="storageUri" Type="System.String" />
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt;" />
      </Parameters>
      <Docs>
        <param name="storageKeyType"><span data-ttu-id="77efa-103">使用する記憶域のキーの型。</span><span class="sxs-lookup"><span data-stu-id="77efa-103">The type of the storage key to use.</span></span>
            <span data-ttu-id="77efa-104">使用可能な値が含まれます: 'StorageAccessKey'、'SharedAccessKey'</span><span class="sxs-lookup"><span data-stu-id="77efa-104">Possible values include: 'StorageAccessKey', 'SharedAccessKey'</span></span></param>
        <param name="storageKey"><span data-ttu-id="77efa-105">使用する記憶域のキー。</span><span class="sxs-lookup"><span data-stu-id="77efa-105">The storage key to use.</span></span>  <span data-ttu-id="77efa-106">記憶域のキーの種類が SharedAccessKey の場合は、前に必ずと、"?."</span><span class="sxs-lookup"><span data-stu-id="77efa-106">If storage key type is SharedAccessKey, it must be preceded with a "?."</span></span></param>
        <param name="storageUri"><span data-ttu-id="77efa-107">使用する記憶域の uri。</span><span class="sxs-lookup"><span data-stu-id="77efa-107">The storage uri to use.</span></span></param>
        <param name="administratorLogin"><span data-ttu-id="77efa-108">SQL 管理者の名前。</span><span class="sxs-lookup"><span data-stu-id="77efa-108">The name of the SQL administrator.</span></span></param>
        <param name="administratorLoginPassword"><span data-ttu-id="77efa-109">SQL 管理者のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="77efa-109">The password of the SQL administrator.</span></span></param>
        <param name="name"><span data-ttu-id="77efa-110">拡張機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="77efa-110">The name of the extension.</span></span></param>
        <param name="type"><span data-ttu-id="77efa-111">拡張機能の型。</span><span class="sxs-lookup"><span data-stu-id="77efa-111">The type of the extension.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="77efa-112">認証の種類。</span><span class="sxs-lookup"><span data-stu-id="77efa-112">The authentication type.</span></span> <span data-ttu-id="77efa-113">使用可能な値が含まれます 'SQL'、'ADPassword'。</span><span class="sxs-lookup"><span data-stu-id="77efa-113">Possible values include: 'SQL', 'ADPassword'</span></span></param>
        <summary>
            <span data-ttu-id="77efa-114">ImportExtensionRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77efa-114">Initializes a new instance of the ImportExtensionRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLogin">
      <MemberSignature Language="C#" Value="public string AdministratorLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AdministratorLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLogin As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLogin : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AdministratorLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLogin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-115">取得または、SQL 管理者の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-115">Gets or sets the name of the SQL administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLoginPassword">
      <MemberSignature Language="C#" Value="public string AdministratorLoginPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLoginPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AdministratorLoginPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLoginPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLoginPassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AdministratorLoginPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLoginPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-116">取得または、SQL 管理者のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-116">Gets or sets the password of the SQL administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As Nullable(Of AuthenticationType)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-117">取得または認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-117">Gets or sets the authentication type.</span></span> <span data-ttu-id="77efa-118">使用可能な値が含まれます 'SQL'、'ADPassword'。</span><span class="sxs-lookup"><span data-stu-id="77efa-118">Possible values include: 'SQL', 'ADPassword'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-119">取得または拡張機能の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-119">Gets or sets the name of the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationMode">
      <MemberSignature Language="C#" Value="public static string OperationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string OperationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.OperationMode" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property OperationMode As String" />
      <MemberSignature Language="F#" Value="member this.OperationMode : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.OperationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-120">インポート操作の実行中の型。</span><span class="sxs-lookup"><span data-stu-id="77efa-120">The type of import operation being performed.</span></span> <span data-ttu-id="77efa-121">これは常にインポートします。</span><span class="sxs-lookup"><span data-stu-id="77efa-121">This is always Import.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageKey">
      <MemberSignature Language="C#" Value="public string StorageKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageKey : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-122">取得または使用する記憶域のキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-122">Gets or sets the storage key to use.</span></span>  <span data-ttu-id="77efa-123">記憶域のキーの種類が SharedAccessKey の場合は、前に必ずと、"?."</span><span class="sxs-lookup"><span data-stu-id="77efa-123">If storage key type is SharedAccessKey, it must be preceded with a "?."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageKeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.StorageKeyType StorageKeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.StorageKeyType StorageKeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageKeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageKeyType As StorageKeyType" />
      <MemberSignature Language="F#" Value="member this.StorageKeyType : Microsoft.Azure.Management.Sql.Models.StorageKeyType with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageKeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageKeyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.StorageKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-124">取得または使用する記憶域のキーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-124">Gets or sets the type of the storage key to use.</span></span> <span data-ttu-id="77efa-125">使用可能な値が含まれます: 'StorageAccessKey'、'SharedAccessKey'</span><span class="sxs-lookup"><span data-stu-id="77efa-125">Possible values include: 'StorageAccessKey', 'SharedAccessKey'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public string StorageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageUri As String" />
      <MemberSignature Language="F#" Value="member this.StorageUri : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-126">取得または使用する記憶域の uri を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-126">Gets or sets the storage uri to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77efa-127">取得または拡張の型を設定します。</span><span class="sxs-lookup"><span data-stu-id="77efa-127">Gets or sets the type of the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="importExtensionRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77efa-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="77efa-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="77efa-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="77efa-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>