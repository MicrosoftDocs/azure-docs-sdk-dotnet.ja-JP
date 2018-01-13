<Type Name="CertificateBaseProperties" FullName="Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties">
  <TypeSignature Language="C#" Value="public class CertificateBaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateBaseProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateBaseProperties" />
  <TypeSignature Language="F#" Value="type CertificateBaseProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateBaseProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ebdb-101">CertificateBaseProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-101">Initializes a new instance of the CertificateBaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateBaseProperties (string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.#ctor(System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional thumbprintAlgorithm As String = null, Optional thumbprint As String = null, Optional format As CertificateFormat = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties : string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat -&gt; Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties (thumbprintAlgorithm, thumbprint, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="1ebdb-102">証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="1ebdb-102">The algorithm of the certificate thumbprint</span></span></param>
        <param name="thumbprint"><span data-ttu-id="1ebdb-103">証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="1ebdb-103">The thumbprint of the certificate</span></span></param>
        <param name="format"><span data-ttu-id="1ebdb-104">証明書の Cer または Pfx のいずれかの形式。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-104">The format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="1ebdb-105">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-105">If omitted, the default is Pfx.</span></span> <span data-ttu-id="1ebdb-106">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="1ebdb-106">Possible values include: 'Pfx', 'Cer'</span></span></param>
        <summary>
            <span data-ttu-id="1ebdb-107">CertificateBaseProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-107">Initializes a new instance of the CertificateBaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ebdb-108">取得または証明書の Cer または Pfx のいずれかの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-108">Gets or sets the format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="1ebdb-109">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-109">If omitted, the default is Pfx.</span></span> <span data-ttu-id="1ebdb-110">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="1ebdb-110">Possible values include: 'Pfx', 'Cer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1ebdb-111">取得または設定、証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="1ebdb-111">Gets or sets the thumbprint of the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1ebdb-112">これにより、名と拇印が一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-112">This must match the thumbprint from the name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateBaseProperties.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ebdb-113">取得または設定、証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="1ebdb-113">Gets or sets the algorithm of the certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1ebdb-114">これは、証明書名の最初の部分と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-114">This must match the first portion of the certificate name.</span></span>
            <span data-ttu-id="1ebdb-115">'SHA1' 現在必要です。</span><span class="sxs-lookup"><span data-stu-id="1ebdb-115">Currently required to be 'SHA1'.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>