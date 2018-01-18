<Type Name="ResourceCertificateAndAcsDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails">
  <TypeSignature Language="C#" Value="public class ResourceCertificateAndAcsDetails : Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceCertificateAndAcsDetails extends Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceCertificateAndAcsDetails&#xA;Inherits ResourceCertificateDetails" />
  <TypeSignature Language="F#" Value="type ResourceCertificateAndAcsDetails = class&#xA;    inherit ResourceCertificateDetails" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AccessControlService")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c42e3-101">ACS の資格情報コンテナーを表す証明書の詳細。</span><span class="sxs-lookup"><span data-stu-id="c42e3-101">Certificate details representing the Vault credentials for ACS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAcsDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c42e3-102">ResourceCertificateAndAcsDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-102">Initializes a new instance of the ResourceCertificateAndAcsDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAcsDetails (string globalAcsNamespace, string globalAcsHostName, string globalAcsRPRealm, byte[] certificate = null, string friendlyName = null, string issuer = null, Nullable&lt;long&gt; resourceId = null, string subject = null, string thumbprint = null, Nullable&lt;DateTime&gt; validFrom = null, Nullable&lt;DateTime&gt; validTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string globalAcsNamespace, string globalAcsHostName, string globalAcsRPRealm, unsigned int8[] certificate, string friendlyName, string issuer, valuetype System.Nullable`1&lt;int64&gt; resourceId, string subject, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validFrom, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.#ctor(System.String,System.String,System.String,System.Byte[],System.String,System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (globalAcsNamespace As String, globalAcsHostName As String, globalAcsRPRealm As String, Optional certificate As Byte() = null, Optional friendlyName As String = null, Optional issuer As String = null, Optional resourceId As Nullable(Of Long) = null, Optional subject As String = null, Optional thumbprint As String = null, Optional validFrom As Nullable(Of DateTime) = null, Optional validTo As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails : string * string * string * byte[] * string * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails (globalAcsNamespace, globalAcsHostName, globalAcsRPRealm, certificate, friendlyName, issuer, resourceId, subject, thumbprint, validFrom, validTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="globalAcsNamespace" Type="System.String" />
        <Parameter Name="globalAcsHostName" Type="System.String" />
        <Parameter Name="globalAcsRPRealm" Type="System.String" />
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
        <param name="globalAcsNamespace"><span data-ttu-id="c42e3-103">ACS 名前空間の名前のサービスのテナント。</span><span class="sxs-lookup"><span data-stu-id="c42e3-103">ACS namespace name - tenant for our service.</span></span></param>
        <param name="globalAcsHostName"><span data-ttu-id="c42e3-104">接続するには、管理ホスト名を Acs です。</span><span class="sxs-lookup"><span data-stu-id="c42e3-104">Acs mgmt host name to connect to.</span></span></param>
        <param name="globalAcsRPRealm"><span data-ttu-id="c42e3-105">グローバルの ACS 名前空間 RP 領域です。</span><span class="sxs-lookup"><span data-stu-id="c42e3-105">Global ACS namespace RP realm.</span></span></param>
        <param name="certificate"><span data-ttu-id="c42e3-106">Base64 エンコードの証明書の生データ文字列。</span><span class="sxs-lookup"><span data-stu-id="c42e3-106">The base64 encoded certificate raw data string.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="c42e3-107">Friendlyname の証明書します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-107">Certificate friendlyname.</span></span></param>
        <param name="issuer"><span data-ttu-id="c42e3-108">証明書の発行者。</span><span class="sxs-lookup"><span data-stu-id="c42e3-108">Certificate issuer.</span></span></param>
        <param name="resourceId"><span data-ttu-id="c42e3-109">資格情報コンテナーのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="c42e3-109">Resource ID of the vault.</span></span></param>
        <param name="subject"><span data-ttu-id="c42e3-110">証明書のサブジェクト名。</span><span class="sxs-lookup"><span data-stu-id="c42e3-110">Certificate Subject Name.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="c42e3-111">証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="c42e3-111">Certificate thumbprint.</span></span></param>
        <param name="validFrom"><span data-ttu-id="c42e3-112">証明書の有効性は、日付時刻を開始します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-112">Certificate Validity start Date time.</span></span></param>
        <param name="validTo"><span data-ttu-id="c42e3-113">証明書の有効終了日の時刻。</span><span class="sxs-lookup"><span data-stu-id="c42e3-113">Certificate Validity End Date time.</span></span></param>
        <summary>
            <span data-ttu-id="c42e3-114">ResourceCertificateAndAcsDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-114">Initializes a new instance of the ResourceCertificateAndAcsDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsHostName">
      <MemberSignature Language="C#" Value="public string GlobalAcsHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsHostName As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsHostName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c42e3-115">取得またはへの接続に acs 管理ホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-115">Gets or sets acs mgmt host name to connect to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsNamespace">
      <MemberSignature Language="C#" Value="public string GlobalAcsNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsNamespace As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsNamespace : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c42e3-116">取得または ACS 名前空間の名前のサービスのテナントを設定します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-116">Gets or sets ACS namespace name - tenant for our service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsRPRealm">
      <MemberSignature Language="C#" Value="public string GlobalAcsRPRealm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsRPRealm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsRPRealm" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsRPRealm As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsRPRealm : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsRPRealm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsRPRealm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c42e3-117">取得またはグローバルの ACS 名前空間 RP レルムを設定します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-117">Gets or sets global ACS namespace RP realm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceCertificateAndAcsDetails.Validate " />
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
            <span data-ttu-id="c42e3-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c42e3-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c42e3-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c42e3-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>