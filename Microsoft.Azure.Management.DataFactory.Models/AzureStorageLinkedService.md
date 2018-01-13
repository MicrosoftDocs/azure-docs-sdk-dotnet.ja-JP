<Type Name="AzureStorageLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService">
  <TypeSignature Language="C#" Value="public class AzureStorageLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureStorageLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureStorage")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="08f4e-101">リンクされたサービス、ストレージ アカウントします。</span><span class="sxs-lookup"><span data-stu-id="08f4e-101">The storage account linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.#ctor" />
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
            <span data-ttu-id="08f4e-102">AzureStorageLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-102">Initializes a new instance of the AzureStorageLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageLinkedService (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecureString connectionString = null, Microsoft.Azure.Management.DataFactory.Models.SecureString sasUri = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecureString connectionString, class Microsoft.Azure.Management.DataFactory.Models.SecureString sasUri, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecureString,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional connectionString As SecureString = null, Optional sasUri As SecureString = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService : System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecureString * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService (additionalProperties, connectVia, description, connectionString, sasUri, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="connectionString" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="sasUri" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="08f4e-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="08f4e-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="08f4e-104">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="08f4e-104">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="08f4e-105">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="08f4e-105">Linked service description.</span></span></param>
        <param name="connectionString"><span data-ttu-id="08f4e-106">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="08f4e-106">The connection string.</span></span> <span data-ttu-id="08f4e-107">SasUri プロパティで相互に排他的であります。</span><span class="sxs-lookup"><span data-stu-id="08f4e-107">It is mutually exclusive with sasUri property.</span></span></param>
        <param name="sasUri"><span data-ttu-id="08f4e-108">Azure ストレージ リソースの SAS URI。</span><span class="sxs-lookup"><span data-stu-id="08f4e-108">SAS URI of the Azure Storage resource.</span></span> <span data-ttu-id="08f4e-109">これは、connectionString プロパティで相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="08f4e-109">It is mutually exclusive with connectionString property.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="08f4e-110">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-110">The encrypted credential used for authentication.</span></span> <span data-ttu-id="08f4e-111">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="08f4e-111">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="08f4e-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="08f4e-112">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="08f4e-113">AzureStorageLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-113">Initializes a new instance of the AzureStorageLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As SecureString" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f4e-114">取得または接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-114">Gets or sets the connection string.</span></span> <span data-ttu-id="08f4e-115">SasUri プロパティで相互に排他的であります。</span><span class="sxs-lookup"><span data-stu-id="08f4e-115">It is mutually exclusive with sasUri property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="08f4e-116">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-116">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="08f4e-117">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="08f4e-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="08f4e-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="08f4e-118">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString SasUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString SasUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.SasUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUri As SecureString" />
      <MemberSignature Language="F#" Value="member this.SasUri : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.SasUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sasUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f4e-119">取得または Azure ストレージ リソースの SAS URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-119">Gets or sets SAS URI of the Azure Storage resource.</span></span> <span data-ttu-id="08f4e-120">これは、connectionString プロパティで相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="08f4e-120">It is mutually exclusive with connectionString property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureStorageLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureStorageLinkedService.Validate " />
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
            <span data-ttu-id="08f4e-121">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="08f4e-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="08f4e-122">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="08f4e-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>