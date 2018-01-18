<Type Name="AppServiceCertificatePatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource">
  <TypeSignature Language="C#" Value="public class AppServiceCertificatePatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificatePatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificatePatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificatePatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="08b45-101">Key Vault のコンテナーを Azure で購入した証明書の ARM リソースです。</span><span class="sxs-lookup"><span data-stu-id="08b45-101">Key Vault container ARM resource for a certificate that is purchased through Azure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificatePatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08b45-102">AppServiceCertificatePatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08b45-102">Initializes a new instance of the AppServiceCertificatePatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificatePatchResource (string id = null, string name = null, string kind = null, string type = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional keyVaultId As String = null, Optional keyVaultSecretName As String = null, Optional provisioningState As Nullable(Of KeyVaultSecretStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource (id, name, kind, type, keyVaultId, keyVaultSecretName, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="08b45-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="08b45-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="08b45-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="08b45-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="08b45-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="08b45-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="08b45-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="08b45-106">Resource type.</span></span></param>
        <param name="keyVaultId"><span data-ttu-id="08b45-107">Key Vault リソース id。</span><span class="sxs-lookup"><span data-stu-id="08b45-107">Key Vault resource Id.</span></span></param>
        <param name="keyVaultSecretName"><span data-ttu-id="08b45-108">Key Vault シークレットの名前です。</span><span class="sxs-lookup"><span data-stu-id="08b45-108">Key Vault secret name.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="08b45-109">Key Vault シークレットの状態です。</span><span class="sxs-lookup"><span data-stu-id="08b45-109">Status of the Key Vault secret.</span></span>
            <span data-ttu-id="08b45-110">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="08b45-110">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span></param>
        <summary>
            <span data-ttu-id="08b45-111">AppServiceCertificatePatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08b45-111">Initializes a new instance of the AppServiceCertificatePatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.KeyVaultId" />
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
            <span data-ttu-id="08b45-112">取得または設定キーの資格情報コンテナーのリソース id。</span><span class="sxs-lookup"><span data-stu-id="08b45-112">Gets or sets key Vault resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.KeyVaultSecretName" />
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
            <span data-ttu-id="08b45-113">取得またはキーの資格情報コンテナーのシークレット名を設定します。</span><span class="sxs-lookup"><span data-stu-id="08b45-113">Gets or sets key Vault secret name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource.ProvisioningState" />
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
            <span data-ttu-id="08b45-114">秘密キー コンテナーの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="08b45-114">Gets status of the Key Vault secret.</span></span> <span data-ttu-id="08b45-115">使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="08b45-115">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>