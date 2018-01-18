<Type Name="AppServiceCertificateResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateResource : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateResource extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2133d-101">Key Vault のコンテナーを Azure で購入した証明書の ARM リソースです。</span><span class="sxs-lookup"><span data-stu-id="2133d-101">Key Vault container ARM resource for a certificate that is purchased through Azure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2133d-102">AppServiceCertificateResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2133d-102">Initializes a new instance of the AppServiceCertificateResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResource (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional keyVaultId As String = null, Optional keyVaultSecretName As String = null, Optional provisioningState As Nullable(Of KeyVaultSecretStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource (location, id, name, kind, type, tags, keyVaultId, keyVaultSecretName, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="2133d-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="2133d-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="2133d-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="2133d-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="2133d-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="2133d-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="2133d-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2133d-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="2133d-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2133d-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="2133d-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="2133d-108">Resource tags.</span></span></param>
        <param name="keyVaultId"><span data-ttu-id="2133d-109">Key Vault リソース id。</span><span class="sxs-lookup"><span data-stu-id="2133d-109">Key Vault resource Id.</span></span></param>
        <param name="keyVaultSecretName"><span data-ttu-id="2133d-110">Key Vault シークレットの名前です。</span><span class="sxs-lookup"><span data-stu-id="2133d-110">Key Vault secret name.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="2133d-111">Key Vault シークレットの状態です。</span><span class="sxs-lookup"><span data-stu-id="2133d-111">Status of the Key Vault secret.</span></span>
            <span data-ttu-id="2133d-112">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="2133d-112">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span></param>
        <summary>
            <span data-ttu-id="2133d-113">AppServiceCertificateResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2133d-113">Initializes a new instance of the AppServiceCertificateResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2133d-114">取得または設定キーの資格情報コンテナーのリソース id。</span><span class="sxs-lookup"><span data-stu-id="2133d-114">Gets or sets key Vault resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2133d-115">取得またはキーの資格情報コンテナーのシークレット名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2133d-115">Gets or sets key Vault secret name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2133d-116">秘密キー コンテナーの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2133d-116">Gets status of the Key Vault secret.</span></span> <span data-ttu-id="2133d-117">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="2133d-117">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServiceCertificateResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2133d-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2133d-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2133d-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2133d-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>