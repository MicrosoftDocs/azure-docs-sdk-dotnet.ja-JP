<Type Name="CertificateImportParameters" FullName="Microsoft.Azure.KeyVault.Models.CertificateImportParameters">
  <TypeSignature Language="C#" Value="public class CertificateImportParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateImportParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateImportParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateImportParameters" />
  <TypeSignature Language="F#" Value="type CertificateImportParameters = class" />
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
            <span data-ttu-id="20983-101">証明書のインポートのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="20983-101">The certificate import parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateImportParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20983-102">CertificateImportParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20983-102">Initializes a new instance of the CertificateImportParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateImportParameters (string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateImportParameters : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.CertificateImportParameters" Usage="new Microsoft.Azure.KeyVault.Models.CertificateImportParameters (base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="base64EncodedCertificate"><span data-ttu-id="20983-103">インポートする証明書オブジェクトの表現を Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="20983-103">Base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="20983-104">この証明書を秘密キーを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="20983-104">This certificate needs to contain the private key.</span></span></param>
        <param name="password"><span data-ttu-id="20983-105">Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。</span><span class="sxs-lookup"><span data-stu-id="20983-105">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span></param>
        <param name="certificatePolicy"><span data-ttu-id="20983-106">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="20983-106">The management policy for the certificate.</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="20983-107">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="20983-107">The attributes of the certificate (optional).</span></span></param>
        <param name="tags"><span data-ttu-id="20983-108">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="20983-108">Application specific metadata in the form of key-value pairs.</span></span></param>
        <summary>
            <span data-ttu-id="20983-109">CertificateImportParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20983-109">Initializes a new instance of the CertificateImportParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64EncodedCertificate">
      <MemberSignature Language="C#" Value="public string Base64EncodedCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Base64EncodedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Base64EncodedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Base64EncodedCertificate As String" />
      <MemberSignature Language="F#" Value="member this.Base64EncodedCertificate : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Base64EncodedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20983-110">取得またはインポートする証明書オブジェクトの base64 でエンコードされた形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="20983-110">Gets or sets base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="20983-111">この証明書を秘密キーを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="20983-111">This certificate needs to contain the private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificateAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateAttributes As CertificateAttributes" />
      <MemberSignature Language="F#" Value="member this.CertificateAttributes : Microsoft.Azure.KeyVault.Models.CertificateAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificateAttributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificateAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20983-112">取得または (省略可能) 証明書の属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="20983-112">Gets or sets the attributes of the certificate (optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificatePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificatePolicy CertificatePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificatePolicy CertificatePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificatePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificatePolicy As CertificatePolicy" />
      <MemberSignature Language="F#" Value="member this.CertificatePolicy : Microsoft.Azure.KeyVault.Models.CertificatePolicy with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificatePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificatePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20983-113">取得または証明書の管理ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="20983-113">Gets or sets the management policy for the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pwd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20983-114">取得または設定 base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。</span><span class="sxs-lookup"><span data-stu-id="20983-114">Gets or sets if the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20983-115">取得またはキー/値ペアの形式でアプリケーション固有のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="20983-115">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateImportParameters.Validate " />
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
            <span data-ttu-id="20983-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="20983-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="20983-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="20983-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>