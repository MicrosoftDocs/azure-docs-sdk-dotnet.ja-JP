<Type Name="CertificateDescription" FullName="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription">
  <TypeSignature Language="C#" Value="public class CertificateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateDescription" />
  <TypeSignature Language="F#" Value="type CertificateDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="98623-101">証明書の詳細</span><span class="sxs-lookup"><span data-stu-id="98623-101">Certificate details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98623-102">CertificateDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="98623-102">Initializes a new instance of the CertificateDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDescription (string thumbprint, string thumbprintSecondary = null, string x509StoreName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintSecondary, string x509StoreName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (thumbprint As String, Optional thumbprintSecondary As String = null, Optional x509StoreName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription : string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription (thumbprint, thumbprintSecondary, x509StoreName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintSecondary" Type="System.String" />
        <Parameter Name="x509StoreName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint"><span data-ttu-id="98623-103">プライマリ証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="98623-103">Thumbprint of the primary certificate</span></span></param>
        <param name="thumbprintSecondary"><span data-ttu-id="98623-104">セカンダリ証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="98623-104">Thumbprint of the secondary certificate</span></span></param>
        <param name="x509StoreName"><span data-ttu-id="98623-105">ローカルの証明書ストアの場所。</span><span class="sxs-lookup"><span data-stu-id="98623-105">The local certificate store location.</span></span>
            <span data-ttu-id="98623-106">使用可能な値が含まれます: 'AddressBook'、'AuthRoot'、'CertificateAuthority'、'許可されていない'、'My'、'Root'、'TrustedPeople'、'TrustedPublisher'</span><span class="sxs-lookup"><span data-stu-id="98623-106">Possible values include: 'AddressBook', 'AuthRoot', 'CertificateAuthority', 'Disallowed', 'My', 'Root', 'TrustedPeople', 'TrustedPublisher'</span></span></param>
        <summary>
            <span data-ttu-id="98623-107">CertificateDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="98623-107">Initializes a new instance of the CertificateDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98623-108">取得または設定プライマリ証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="98623-108">Gets or sets thumbprint of the primary certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintSecondary">
      <MemberSignature Language="C#" Value="public string ThumbprintSecondary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.ThumbprintSecondary" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintSecondary As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintSecondary : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.ThumbprintSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintSecondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98623-109">取得または設定セカンダリ証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="98623-109">Gets or sets thumbprint of the secondary certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98623-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="98623-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="98623-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="98623-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="X509StoreName">
      <MemberSignature Language="C#" Value="public string X509StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string X509StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.X509StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property X509StoreName As String" />
      <MemberSignature Language="F#" Value="member this.X509StoreName : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription.X509StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="x509StoreName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98623-112">取得またはローカルの証明書ストアの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="98623-112">Gets or sets the local certificate store location.</span></span> <span data-ttu-id="98623-113">使用可能な値が含まれます: 'AddressBook'、'AuthRoot'、'CertificateAuthority'、'許可されていない'、'My'、'Root'、'TrustedPeople'、'TrustedPublisher'</span><span class="sxs-lookup"><span data-stu-id="98623-113">Possible values include: 'AddressBook', 'AuthRoot', 'CertificateAuthority', 'Disallowed', 'My', 'Root', 'TrustedPeople', 'TrustedPublisher'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>