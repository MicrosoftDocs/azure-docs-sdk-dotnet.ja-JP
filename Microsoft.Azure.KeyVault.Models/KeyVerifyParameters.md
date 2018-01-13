<Type Name="KeyVerifyParameters" FullName="Microsoft.Azure.KeyVault.Models.KeyVerifyParameters">
  <TypeSignature Language="C#" Value="public class KeyVerifyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVerifyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVerifyParameters" />
  <TypeSignature Language="F#" Value="type KeyVerifyParameters = class" />
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
            <span data-ttu-id="a8739-101">キーは、パラメーターを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8739-101">The key verify parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVerifyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a8739-102">KeyVerifyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8739-102">Initializes a new instance of the KeyVerifyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVerifyParameters (string algorithm, byte[] digest, byte[] signature);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string algorithm, unsigned int8[] digest, unsigned int8[] signature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.#ctor(System.String,System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (algorithm As String, digest As Byte(), signature As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyVerifyParameters : string * byte[] * byte[] -&gt; Microsoft.Azure.KeyVault.Models.KeyVerifyParameters" Usage="new Microsoft.Azure.KeyVault.Models.KeyVerifyParameters (algorithm, digest, signature)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="algorithm"><span data-ttu-id="a8739-103">署名/検証アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="a8739-103">The signing/verification algorithm.</span></span> <span data-ttu-id="a8739-104">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8739-104">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="a8739-105">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="a8739-105">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span></param>
        <param name="digest"><span data-ttu-id="a8739-106">ダイジェストの署名に使用します。</span><span class="sxs-lookup"><span data-stu-id="a8739-106">The digest used for signing.</span></span></param>
        <param name="signature"><span data-ttu-id="a8739-107">検証対象の署名。</span><span class="sxs-lookup"><span data-stu-id="a8739-107">The signature to be verified.</span></span></param>
        <summary>
            <span data-ttu-id="a8739-108">KeyVerifyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8739-108">Initializes a new instance of the KeyVerifyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="alg")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8739-109">取得または署名/検証アルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8739-109">Gets or sets the signing/verification algorithm.</span></span> <span data-ttu-id="a8739-110">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8739-110">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="a8739-111">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="a8739-111">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Digest">
      <MemberSignature Language="C#" Value="public byte[] Digest { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Digest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Digest" />
      <MemberSignature Language="VB.NET" Value="Public Property Digest As Byte()" />
      <MemberSignature Language="F#" Value="member this.Digest : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Digest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="digest")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8739-112">取得または署名に使用されるダイジェストを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8739-112">Gets or sets the digest used for signing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Signature">
      <MemberSignature Language="C#" Value="public byte[] Signature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Signature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Signature" />
      <MemberSignature Language="VB.NET" Value="Public Property Signature As Byte()" />
      <MemberSignature Language="F#" Value="member this.Signature : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Signature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8739-113">取得または検証する署名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8739-113">Gets or sets the signature to be verified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVerifyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVerifyParameters.Validate " />
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
            <span data-ttu-id="a8739-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a8739-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a8739-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a8739-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>