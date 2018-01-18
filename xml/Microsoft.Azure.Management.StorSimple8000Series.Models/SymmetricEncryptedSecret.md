<Type Name="SymmetricEncryptedSecret" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret">
  <TypeSignature Language="C#" Value="public class SymmetricEncryptedSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SymmetricEncryptedSecret extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class SymmetricEncryptedSecret" />
  <TypeSignature Language="F#" Value="type SymmetricEncryptedSecret = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0c47-101">対称暗号化キーを使用して暗号化されたシークレットを表します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-101">Represents the secrets encrypted using Symmetric Encryption Key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SymmetricEncryptedSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c0c47-102">SymmetricEncryptedSecret クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-102">Initializes a new instance of the SymmetricEncryptedSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SymmetricEncryptedSecret (string value, Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string valueCertificateThumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string valueCertificateThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret : string * Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret (value, encryptionAlgorithm, valueCertificateThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="encryptionAlgorithm" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm" />
        <Parameter Name="valueCertificateThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="c0c47-103">シークレット自体の値。</span><span class="sxs-lookup"><span data-stu-id="c0c47-103">The value of the secret itself.</span></span> <span data-ttu-id="c0c47-104">機密情報がプレーン テキストまたは null の場合、EncryptionAlgorithm は none になります。</span><span class="sxs-lookup"><span data-stu-id="c0c47-104">If the secret is in plaintext or null then EncryptionAlgorithm will be none.</span></span></param>
        <param name="encryptionAlgorithm"><span data-ttu-id="c0c47-105">「値」の暗号化に使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="c0c47-105">The algorithm used to encrypt the "Value".</span></span> <span data-ttu-id="c0c47-106">使用可能な値が含まれます 'None'、'AES256'、'RSAES_PKCS1_v_1_5'。</span><span class="sxs-lookup"><span data-stu-id="c0c47-106">Possible values include: 'None', 'AES256', 'RSAES_PKCS1_v_1_5'</span></span></param>
        <param name="valueCertificateThumbprint"><span data-ttu-id="c0c47-107">「値」の暗号化に使用された証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="c0c47-107">The thumbprint of the cert that was used to encrypt "Value".</span></span></param>
        <summary>
            <span data-ttu-id="c0c47-108">SymmetricEncryptedSecret クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-108">Initializes a new instance of the SymmetricEncryptedSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionAlgorithm As EncryptionAlgorithm" />
      <MemberSignature Language="F#" Value="member this.EncryptionAlgorithm : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0c47-109">取得または「値」の暗号化に使用されるアルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-109">Gets or sets the algorithm used to encrypt the "Value".</span></span> <span data-ttu-id="c0c47-110">使用可能な値が含まれます 'None'、'AES256'、'RSAES_PKCS1_v_1_5'。</span><span class="sxs-lookup"><span data-stu-id="c0c47-110">Possible values include: 'None', 'AES256', 'RSAES_PKCS1_v_1_5'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="symmetricEncryptedSecret.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c0c47-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0c47-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0c47-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c0c47-113">取得またはシークレット自体の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-113">Gets or sets the value of the secret itself.</span></span> <span data-ttu-id="c0c47-114">機密情報がプレーン テキストまたは null の場合、EncryptionAlgorithm は none になります。</span><span class="sxs-lookup"><span data-stu-id="c0c47-114">If the secret is in plaintext or null then EncryptionAlgorithm will be none.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueCertificateThumbprint">
      <MemberSignature Language="C#" Value="public string ValueCertificateThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValueCertificateThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.ValueCertificateThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property ValueCertificateThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.ValueCertificateThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.ValueCertificateThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="valueCertificateThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0c47-115">取得または「値」の暗号化に使用された証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0c47-115">Gets or sets the thumbprint of the cert that was used to encrypt "Value".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>