<Type Name="CertificateIssuerSetParameters" FullName="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters">
  <TypeSignature Language="C#" Value="public class CertificateIssuerSetParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateIssuerSetParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateIssuerSetParameters" />
  <TypeSignature Language="F#" Value="type CertificateIssuerSetParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29e8a-101">証明書の発行者は、パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-101">The certificate issuer set parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerSetParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-102">CertificateIssuerSetParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-102">Initializes a new instance of the CertificateIssuerSetParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerSetParameters (string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.#ctor(System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters : string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes -&gt; Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters" Usage="new Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters (provider, credentials, organizationDetails, attributes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="29e8a-103">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="29e8a-103">The issuer provider.</span></span></param>
        <param name="credentials"><span data-ttu-id="29e8a-104">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="29e8a-104">The credentials to be used for the issuer.</span></span></param>
        <param name="organizationDetails"><span data-ttu-id="29e8a-105">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="29e8a-105">Details of the organization as provided to the issuer.</span></span></param>
        <param name="attributes"><span data-ttu-id="29e8a-106">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="29e8a-106">Attributes of the issuer object.</span></span></param>
        <summary>
            <span data-ttu-id="29e8a-107">CertificateIssuerSetParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-107">Initializes a new instance of the CertificateIssuerSetParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As IssuerAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.IssuerAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-108">取得または発行元のオブジェクトの属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-108">Gets or sets attributes of the issuer object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As IssuerCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.KeyVault.Models.IssuerCredentials with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-109">取得または発行者のための資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-109">Gets or sets the credentials to be used for the issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrganizationDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.OrganizationDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property OrganizationDetails As OrganizationDetails" />
      <MemberSignature Language="F#" Value="member this.OrganizationDetails : Microsoft.Azure.KeyVault.Models.OrganizationDetails with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.OrganizationDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="org_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.OrganizationDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-110">取得または発行者に提供されるように、組織の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-110">Gets or sets details of the organization as provided to the issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-111">取得または発行者プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-111">Gets or sets the issuer provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateIssuerSetParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29e8a-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="29e8a-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29e8a-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="29e8a-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>