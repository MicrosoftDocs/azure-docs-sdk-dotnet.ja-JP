<Type Name="AzureBatchLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService">
  <TypeSignature Language="C#" Value="public class AzureBatchLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBatchLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBatchLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureBatchLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureBatch")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="75ac7-101">Azure Batch のリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="75ac7-101">Azure Batch linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBatchLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.#ctor" />
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
            <span data-ttu-id="75ac7-102">AzureBatchLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-102">Initializes a new instance of the AzureBatchLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBatchLinkedService (object accountName, object batchUri, object poolName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecureString accessKey = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object accountName, object batchUri, object poolName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecureString accessKey, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.#ctor(System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As Object, batchUri As Object, poolName As Object, linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional accessKey As SecureString = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService : obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService (accountName, batchUri, poolName, linkedServiceName, additionalProperties, connectVia, description, accessKey, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.Object" />
        <Parameter Name="batchUri" Type="System.Object" />
        <Parameter Name="poolName" Type="System.Object" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="accessKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="75ac7-103">Azure Batch アカウント名。</span><span class="sxs-lookup"><span data-stu-id="75ac7-103">The Azure Batch account name.</span></span> <span data-ttu-id="75ac7-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="batchUri"><span data-ttu-id="75ac7-105">Azure Batch の URI。</span><span class="sxs-lookup"><span data-stu-id="75ac7-105">The Azure Batch URI.</span></span> <span data-ttu-id="75ac7-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="poolName"><span data-ttu-id="75ac7-107">Azure Batch プールの名前。</span><span class="sxs-lookup"><span data-stu-id="75ac7-107">The Azure Batch pool name.</span></span> <span data-ttu-id="75ac7-108">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-108">Type: string (or Expression with resultType string).</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="75ac7-109">Azure Storage のリンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="75ac7-109">The Azure Storage linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="75ac7-110">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="75ac7-110">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="75ac7-111">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="75ac7-111">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="75ac7-112">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="75ac7-112">Linked service description.</span></span></param>
        <param name="accessKey"><span data-ttu-id="75ac7-113">Azure Batch アカウント アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="75ac7-113">The Azure Batch account access key.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="75ac7-114">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-114">The encrypted credential used for authentication.</span></span> <span data-ttu-id="75ac7-115">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="75ac7-115">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="75ac7-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-116">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="75ac7-117">AzureBatchLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-117">Initializes a new instance of the AzureBatchLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.AccessKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75ac7-118">取得または Azure Batch アカウント アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-118">Gets or sets the Azure Batch account access key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public object AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As Object" />
      <MemberSignature Language="F#" Value="member this.AccountName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75ac7-119">取得または Azure Batch アカウント名を設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-119">Gets or sets the Azure Batch account name.</span></span> <span data-ttu-id="75ac7-120">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-120">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchUri">
      <MemberSignature Language="C#" Value="public object BatchUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BatchUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.BatchUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchUri As Object" />
      <MemberSignature Language="F#" Value="member this.BatchUri : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.BatchUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.batchUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75ac7-121">取得または Azure Batch の URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-121">Gets or sets the Azure Batch URI.</span></span> <span data-ttu-id="75ac7-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-122">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="75ac7-123">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-123">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="75ac7-124">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="75ac7-124">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="75ac7-125">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75ac7-126">取得または Azure Storage のリンクされたサービス参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-126">Gets or sets the Azure Storage linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolName">
      <MemberSignature Language="C#" Value="public object PoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.PoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolName As Object" />
      <MemberSignature Language="F#" Value="member this.PoolName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.PoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.poolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75ac7-127">取得または Azure Batch プールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-127">Gets or sets the Azure Batch pool name.</span></span> <span data-ttu-id="75ac7-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="75ac7-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBatchLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureBatchLinkedService.Validate " />
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
            <span data-ttu-id="75ac7-129">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="75ac7-129">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="75ac7-130">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="75ac7-130">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>