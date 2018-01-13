<Type Name="AppServiceCertificateOrderInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateOrderInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateOrderInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateOrderInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrderInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="394d6-101">SSL 証明書の発注書です。</span><span class="sxs-lookup"><span data-stu-id="394d6-101">SSL certificate purchase order.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="394d6-102">AppServiceCertificateOrderInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="394d6-102">Initializes a new instance of the AppServiceCertificateOrderInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; certificates = null, string distinguishedName = null, string domainVerificationToken = null, Nullable&lt;int&gt; validityInYears = null, Nullable&lt;int&gt; keySize = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; productType = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt; status = null, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails signedCertificate = null, string csr = null, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails intermediate = null, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails root = null, string serialNumber = null, Nullable&lt;DateTime&gt; lastCertificateIssuanceTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;bool&gt; isPrivateKeyExternal = null, System.Collections.Generic.IList&lt;string&gt; appServiceCertificateNotRenewableReasons = null, Nullable&lt;DateTime&gt; nextAutoRenewalTimeStamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; certificates, string distinguishedName, string domainVerificationToken, valuetype System.Nullable`1&lt;int32&gt; validityInYears, valuetype System.Nullable`1&lt;int32&gt; keySize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; productType, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt; status, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails signedCertificate, string csr, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails intermediate, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails root, string serialNumber, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastCertificateIssuanceTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;bool&gt; isPrivateKeyExternal, class System.Collections.Generic.IList`1&lt;string&gt; appServiceCertificateNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextAutoRenewalTimeStamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus},Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional certificates As IDictionary(Of String, AppServiceCertificate) = null, Optional distinguishedName As String = null, Optional domainVerificationToken As String = null, Optional validityInYears As Nullable(Of Integer) = null, Optional keySize As Nullable(Of Integer) = null, Optional productType As Nullable(Of CertificateProductType) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of CertificateOrderStatus) = null, Optional signedCertificate As CertificateDetails = null, Optional csr As String = null, Optional intermediate As CertificateDetails = null, Optional root As CertificateDetails = null, Optional serialNumber As String = null, Optional lastCertificateIssuanceTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional isPrivateKeyExternal As Nullable(Of Boolean) = null, Optional appServiceCertificateNotRenewableReasons As IList(Of String) = null, Optional nextAutoRenewalTimeStamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails * string * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner (location, id, name, type, tags, certificates, distinguishedName, domainVerificationToken, validityInYears, keySize, productType, autoRenew, provisioningState, status, signedCertificate, csr, intermediate, root, serialNumber, lastCertificateIssuanceTime, expirationTime, isPrivateKeyExternal, appServiceCertificateNotRenewableReasons, nextAutoRenewalTimeStamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt;" />
        <Parameter Name="distinguishedName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
        <Parameter Name="validityInYears" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="productType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt;" />
        <Parameter Name="signedCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" />
        <Parameter Name="csr" Type="System.String" />
        <Parameter Name="intermediate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" />
        <Parameter Name="root" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="lastCertificateIssuanceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="isPrivateKeyExternal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServiceCertificateNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextAutoRenewalTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="certificates">To be added.</param>
        <param name="distinguishedName">To be added.</param>
        <param name="domainVerificationToken">To be added.</param>
        <param name="validityInYears">To be added.</param>
        <param name="keySize">To be added.</param>
        <param name="productType">To be added.</param>
        <param name="autoRenew">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="status">To be added.</param>
        <param name="signedCertificate">To be added.</param>
        <param name="csr">To be added.</param>
        <param name="intermediate">To be added.</param>
        <param name="root">To be added.</param>
        <param name="serialNumber">To be added.</param>
        <param name="lastCertificateIssuanceTime">To be added.</param>
        <param name="expirationTime">To be added.</param>
        <param name="isPrivateKeyExternal">To be added.</param>
        <param name="appServiceCertificateNotRenewableReasons">To be added.</param>
        <param name="nextAutoRenewalTimeStamp">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppServiceCertificateNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.AppServiceCertificateNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServiceCertificateNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-103">取得またはなぜアプリ サービスの証明書更新可能な時点では、現在の理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-103">Gets or sets reasons why App Service Certificate is not renewable at the current moment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-104">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt;、証明書は、期限が切れたときに、自動的に更新する場合は、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt。/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="394d6-104">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the certificate should be automatically renewed when it expires; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IDictionary(Of String, AppServiceCertificate)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-105">取得または秘密キー コンテナーの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-105">Gets or sets state of the Key Vault secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public string Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As String" />
      <MemberSignature Language="F#" Value="member this.Csr : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-106">取得またはこの順序用に作成された最後の CSR を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-106">Gets or sets last CSR that was created for this order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistinguishedName">
      <MemberSignature Language="C#" Value="public string DistinguishedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DistinguishedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.DistinguishedName" />
      <MemberSignature Language="VB.NET" Value="Public Property DistinguishedName As String" />
      <MemberSignature Language="F#" Value="member this.DistinguishedName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.DistinguishedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.distinguishedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-107">取得または識別名の証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-107">Gets or sets certificate distinguished name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainVerificationToken">
      <MemberSignature Language="C#" Value="public string DomainVerificationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainVerificationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.DomainVerificationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainVerificationToken As String" />
      <MemberSignature Language="F#" Value="member this.DomainVerificationToken : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.DomainVerificationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainVerificationToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-108">ドメインの確認トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-108">Gets domain verification token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-109">証明書の有効期限の時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-109">Gets certificate expiration time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Intermediate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Intermediate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Intermediate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Intermediate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Intermediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intermediate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-110">中級レベルの証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-110">Gets intermediate certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyExternal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrivateKeyExternal { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrivateKeyExternal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.IsPrivateKeyExternal" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivateKeyExternal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrivateKeyExternal : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.IsPrivateKeyExternal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPrivateKeyExternal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-111">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 秘密キーは、外部、それ以外の場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="394d6-111">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if private key is external; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keySize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-112">取得または証明書のキー サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-112">Gets or sets certificate key size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCertificateIssuanceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastCertificateIssuanceTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastCertificateIssuanceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.LastCertificateIssuanceTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCertificateIssuanceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastCertificateIssuanceTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.LastCertificateIssuanceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastCertificateIssuanceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-113">前回の発行の証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-113">Gets certificate last issuance time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextAutoRenewalTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextAutoRenewalTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextAutoRenewalTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.NextAutoRenewalTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextAutoRenewalTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextAutoRenewalTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.NextAutoRenewalTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextAutoRenewalTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; ProductType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; ProductType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ProductType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductType As Nullable(Of CertificateProductType)" />
      <MemberSignature Language="F#" Value="member this.ProductType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ProductType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.productType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-114">取得または証明書の製品の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-114">Gets or sets certificate product type.</span></span> <span data-ttu-id="394d6-115">使用可能な値が含まれます: 'StandardDomainValidatedSsl'、'StandardDomainValidatedWildCardSsl'</span><span class="sxs-lookup"><span data-stu-id="394d6-115">Possible values include: 'StandardDomainValidatedSsl', 'StandardDomainValidatedWildCardSsl'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-116">証明書の順序の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-116">Gets status of certificate order.</span></span> <span data-ttu-id="394d6-117">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="394d6-117">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Root">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Root" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Root As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Root : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Root" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.root")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-118">証明書のルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-118">Gets root certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-119">証明書の現在のシリアル番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-119">Gets current serial number of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.SignedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignedCertificate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.SignedCertificate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.SignedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.signedCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-120">証明書に署名を取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-120">Gets signed certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CertificateOrderStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-121">現在の注文ステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="394d6-121">Gets current order status.</span></span> <span data-ttu-id="394d6-122">使用可能な値が含まれます: 'Pendingissuance'、'発行'、'無効'、'キャンセル'、'拒否'、'Pendingrevocation'、'PendingRekey'、'未使用'、'有効期限が切れた'、'NotSubmitted'</span><span class="sxs-lookup"><span data-stu-id="394d6-122">Possible values include: 'Pendingissuance', 'Issued', 'Revoked', 'Canceled', 'Denied', 'Pendingrevocation', 'PendingRekey', 'Unused', 'Expired', 'NotSubmitted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServiceCertificateOrderInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="394d6-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="394d6-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="394d6-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="394d6-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidityInYears">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ValidityInYears { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ValidityInYears" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ValidityInYears" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidityInYears As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ValidityInYears : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner.ValidityInYears" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.validityInYears")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394d6-125">取得または年単位 (1 ~ 3 の範囲である必要があります) で期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="394d6-125">Gets or sets duration in years (must be between 1 and 3).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>