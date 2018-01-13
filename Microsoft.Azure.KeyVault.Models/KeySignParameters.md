<Type Name="KeySignParameters" FullName="Microsoft.Azure.KeyVault.Models.KeySignParameters">
  <TypeSignature Language="C#" Value="public class KeySignParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeySignParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeySignParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class KeySignParameters" />
  <TypeSignature Language="F#" Value="type KeySignParameters = class" />
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
            <span data-ttu-id="cee38-101">キーの操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cee38-101">The key operations parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeySignParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cee38-102">KeySignParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cee38-102">Initializes a new instance of the KeySignParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeySignParameters (string algorithm, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string algorithm, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (algorithm As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeySignParameters : string * byte[] -&gt; Microsoft.Azure.KeyVault.Models.KeySignParameters" Usage="new Microsoft.Azure.KeyVault.Models.KeySignParameters (algorithm, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="algorithm"><span data-ttu-id="cee38-103">署名/検証アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="cee38-103">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="cee38-104">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="cee38-104">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="cee38-105">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="cee38-105">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span></param>
        <param name="value">To be added.</param>
        <summary>
            <span data-ttu-id="cee38-106">KeySignParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cee38-106">Initializes a new instance of the KeySignParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeySignParameters.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeySignParameters.Algorithm" />
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
            <span data-ttu-id="cee38-107">取得または署名/検証アルゴリズム識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="cee38-107">Gets or sets the signing/verification algorithm identifier.</span></span> <span data-ttu-id="cee38-108">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="cee38-108">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="cee38-109">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="cee38-109">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keySignParameters.Validate " />
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
            <span data-ttu-id="cee38-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="cee38-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cee38-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cee38-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public byte[] Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeySignParameters.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Byte()" />
      <MemberSignature Language="F#" Value="member this.Value : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeySignParameters.Value" />
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
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>