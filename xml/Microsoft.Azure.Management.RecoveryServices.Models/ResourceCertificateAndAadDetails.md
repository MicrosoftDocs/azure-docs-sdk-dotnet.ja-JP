<Type Name="ResourceCertificateAndAadDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails">
  <TypeSignature Language="C#" Value="public class ResourceCertificateAndAadDetails : Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceCertificateAndAadDetails extends Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceCertificateAndAadDetails&#xA;Inherits ResourceCertificateDetails" />
  <TypeSignature Language="F#" Value="type ResourceCertificateAndAadDetails = class&#xA;    inherit ResourceCertificateDetails" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureActiveDirectory")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5a495-101">AAD の資格情報コンテナーを表す証明書の詳細。</span><span class="sxs-lookup"><span data-stu-id="5a495-101">Certificate details representing the Vault credentials for AAD.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAadDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5a495-102">ResourceCertificateAndAadDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5a495-102">Initializes a new instance of the ResourceCertificateAndAadDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAadDetails (string aadAuthority, string aadTenantId, string servicePrincipalClientId, string servicePrincipalObjectId, string azureManagementEndpointAudience, byte[] certificate = null, string friendlyName = null, string issuer = null, Nullable&lt;long&gt; resourceId = null, string subject = null, string thumbprint = null, Nullable&lt;DateTime&gt; validFrom = null, Nullable&lt;DateTime&gt; validTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string aadAuthority, string aadTenantId, string servicePrincipalClientId, string servicePrincipalObjectId, string azureManagementEndpointAudience, unsigned int8[] certificate, string friendlyName, string issuer, valuetype System.Nullable`1&lt;int64&gt; resourceId, string subject, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validFrom, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.#ctor(System.String,System.String,System.String,System.String,System.String,System.Byte[],System.String,System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (aadAuthority As String, aadTenantId As String, servicePrincipalClientId As String, servicePrincipalObjectId As String, azureManagementEndpointAudience As String, Optional certificate As Byte() = null, Optional friendlyName As String = null, Optional issuer As String = null, Optional resourceId As Nullable(Of Long) = null, Optional subject As String = null, Optional thumbprint As String = null, Optional validFrom As Nullable(Of DateTime) = null, Optional validTo As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails : string * string * string * string * string * byte[] * string * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails (aadAuthority, aadTenantId, servicePrincipalClientId, servicePrincipalObjectId, azureManagementEndpointAudience, certificate, friendlyName, issuer, resourceId, subject, thumbprint, validFrom, validTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="aadAuthority" Type="System.String" />
        <Parameter Name="aadTenantId" Type="System.String" />
        <Parameter Name="servicePrincipalClientId" Type="System.String" />
        <Parameter Name="servicePrincipalObjectId" Type="System.String" />
        <Parameter Name="azureManagementEndpointAudience" Type="System.String" />
        <Parameter Name="certificate" Type="System.Byte[]" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="resourceId" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="validFrom" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="validTo" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="aadAuthority"><span data-ttu-id="5a495-103">AAD テナントの証明機関。</span><span class="sxs-lookup"><span data-stu-id="5a495-103">AAD tenant authority.</span></span></param>
        <param name="aadTenantId"><span data-ttu-id="5a495-104">AAD テナント id。</span><span class="sxs-lookup"><span data-stu-id="5a495-104">AAD tenant Id.</span></span></param>
        <param name="servicePrincipalClientId"><span data-ttu-id="5a495-105">AAD サービス プリンシパルのクライアント Id。</span><span class="sxs-lookup"><span data-stu-id="5a495-105">AAD service principal clientId.</span></span></param>
        <param name="servicePrincipalObjectId"><span data-ttu-id="5a495-106">AAD はサービス プリンシパルのオブジェクト Id です。</span><span class="sxs-lookup"><span data-stu-id="5a495-106">AAD service principal ObjectId.</span></span></param>
        <param name="azureManagementEndpointAudience"><span data-ttu-id="5a495-107">Azure の管理エンドポイントの対象ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="5a495-107">Azure Management Endpoint Audience.</span></span></param>
        <param name="certificate"><span data-ttu-id="5a495-108">Base64 エンコードの証明書の生データ文字列。</span><span class="sxs-lookup"><span data-stu-id="5a495-108">The base64 encoded certificate raw data string.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="5a495-109">Friendlyname の証明書します。</span><span class="sxs-lookup"><span data-stu-id="5a495-109">Certificate friendlyname.</span></span></param>
        <param name="issuer"><span data-ttu-id="5a495-110">証明書の発行者。</span><span class="sxs-lookup"><span data-stu-id="5a495-110">Certificate issuer.</span></span></param>
        <param name="resourceId"><span data-ttu-id="5a495-111">資格情報コンテナーのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="5a495-111">Resource ID of the vault.</span></span></param>
        <param name="subject"><span data-ttu-id="5a495-112">証明書のサブジェクト名。</span><span class="sxs-lookup"><span data-stu-id="5a495-112">Certificate Subject Name.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="5a495-113">証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="5a495-113">Certificate thumbprint.</span></span></param>
        <param name="validFrom"><span data-ttu-id="5a495-114">証明書の有効性は、日付時刻を開始します。</span><span class="sxs-lookup"><span data-stu-id="5a495-114">Certificate Validity start Date time.</span></span></param>
        <param name="validTo"><span data-ttu-id="5a495-115">証明書の有効終了日の時刻。</span><span class="sxs-lookup"><span data-stu-id="5a495-115">Certificate Validity End Date time.</span></span></param>
        <summary>
            <span data-ttu-id="5a495-116">ResourceCertificateAndAadDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5a495-116">Initializes a new instance of the ResourceCertificateAndAadDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadAuthority">
      <MemberSignature Language="C#" Value="public string AadAuthority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AadAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadAuthority" />
      <MemberSignature Language="VB.NET" Value="Public Property AadAuthority As String" />
      <MemberSignature Language="F#" Value="member this.AadAuthority : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aadAuthority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a495-117">取得または AAD テナント機関を設定します。</span><span class="sxs-lookup"><span data-stu-id="5a495-117">Gets or sets AAD tenant authority.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadTenantId">
      <MemberSignature Language="C#" Value="public string AadTenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AadTenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadTenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property AadTenantId As String" />
      <MemberSignature Language="F#" Value="member this.AadTenantId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadTenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aadTenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a495-118">取得または設定 AAD テナント id。</span><span class="sxs-lookup"><span data-stu-id="5a495-118">Gets or sets AAD tenant Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureManagementEndpointAudience">
      <MemberSignature Language="C#" Value="public string AzureManagementEndpointAudience { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureManagementEndpointAudience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AzureManagementEndpointAudience" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureManagementEndpointAudience As String" />
      <MemberSignature Language="F#" Value="member this.AzureManagementEndpointAudience : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AzureManagementEndpointAudience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureManagementEndpointAudience")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a495-119">取得または azure の管理エンドポイントの対象ユーザーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5a495-119">Gets or sets azure Management Endpoint Audience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalClientId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalClientId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalClientId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servicePrincipalClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a495-120">取得または AAD サービス プリンシパルのクライアント Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="5a495-120">Gets or sets AAD service principal clientId.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalObjectId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalObjectId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servicePrincipalObjectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a495-121">取得または設定 AAD サービスのプリンシパルの ObjectId。</span><span class="sxs-lookup"><span data-stu-id="5a495-121">Gets or sets AAD service principal ObjectId.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceCertificateAndAadDetails.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5a495-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5a495-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5a495-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5a495-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>