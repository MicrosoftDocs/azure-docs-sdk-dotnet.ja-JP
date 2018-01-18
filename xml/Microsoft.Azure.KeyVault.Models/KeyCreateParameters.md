<Type Name="KeyCreateParameters" FullName="Microsoft.Azure.KeyVault.Models.KeyCreateParameters">
  <TypeSignature Language="C#" Value="public class KeyCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyCreateParameters" />
  <TypeSignature Language="F#" Value="type KeyCreateParameters = class" />
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
            <span data-ttu-id="01bbc-101">キーは、パラメーターを作成します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-101">The key create parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01bbc-102">KeyCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-102">Initializes a new instance of the KeyCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyCreateParameters (string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.#ctor(System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyCreateParameters : string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.KeyVault.Models.KeyCreateParameters" Usage="new Microsoft.Azure.KeyVault.Models.KeyCreateParameters (kty, keySize, keyOps, keyAttributes, tags, curve)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty"><span data-ttu-id="01bbc-103">作成するキーの型。</span><span class="sxs-lookup"><span data-stu-id="01bbc-103">The type of key to create.</span></span> <span data-ttu-id="01bbc-104">有効な値は、JsonWebKeyType を参照してください。</span><span class="sxs-lookup"><span data-stu-id="01bbc-104">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="01bbc-105">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="01bbc-105">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span></param>
        <param name="keySize"><span data-ttu-id="01bbc-106">キーのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="01bbc-106">The key size in bytes.</span></span> <span data-ttu-id="01bbc-107">たとえば、1024 または</span><span class="sxs-lookup"><span data-stu-id="01bbc-107">For example, 1024 or</span></span>
            2048.</param>
        <param name="keyOps">To be added.</param>
        <param name="keyAttributes">To be added.</param>
        <param name="tags"><span data-ttu-id="01bbc-108">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="01bbc-108">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="curve"><span data-ttu-id="01bbc-109">楕円曲線の名前です。</span><span class="sxs-lookup"><span data-stu-id="01bbc-109">Elliptic curve name.</span></span> <span data-ttu-id="01bbc-110">有効な値は、JsonWebKeyCurveName を参照してください。</span><span class="sxs-lookup"><span data-stu-id="01bbc-110">For valid values, see JsonWebKeyCurveName.</span></span> <span data-ttu-id="01bbc-111">使用可能な値が含まれます: 'P-256'、'P-384'、'P-521'、'SECP256K1'</span><span class="sxs-lookup"><span data-stu-id="01bbc-111">Possible values include: 'P-256', 'P-384', 'P-521', 'SECP256K1'</span></span></param>
        <summary>
            <span data-ttu-id="01bbc-112">KeyCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-112">Initializes a new instance of the KeyCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Curve">
      <MemberSignature Language="C#" Value="public string Curve { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Curve" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Curve" />
      <MemberSignature Language="VB.NET" Value="Public Property Curve As String" />
      <MemberSignature Language="F#" Value="member this.Curve : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Curve" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="crv")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01bbc-113">楕円曲線名前設定または取得します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-113">Gets or sets elliptic curve name.</span></span> <span data-ttu-id="01bbc-114">有効な値は、JsonWebKeyCurveName を参照してください。</span><span class="sxs-lookup"><span data-stu-id="01bbc-114">For valid values, see JsonWebKeyCurveName.</span></span> <span data-ttu-id="01bbc-115">使用可能な値が含まれます: 'P-256'、'P-384'、'P-521'、'SECP256K1'</span><span class="sxs-lookup"><span data-stu-id="01bbc-115">Possible values include: 'P-256', 'P-384', 'P-521', 'SECP256K1'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.KeyAttributes KeyAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.KeyAttributes KeyAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeyAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyAttributes As KeyAttributes" />
      <MemberSignature Language="F#" Value="member this.KeyAttributes : Microsoft.Azure.KeyVault.Models.KeyAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeyAttributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.KeyAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyOps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeyOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeyOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeyOps" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyOps As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeyOps : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeyOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key_ops")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key_size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01bbc-116">取得またはキーのサイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-116">Gets or sets the key size in bytes.</span></span> <span data-ttu-id="01bbc-117">たとえば、1024 または 2048。</span><span class="sxs-lookup"><span data-stu-id="01bbc-117">For example, 1024 or 2048.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Kty" />
      <MemberSignature Language="VB.NET" Value="Public Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kty")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01bbc-118">取得または作成するキーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-118">Gets or sets the type of key to create.</span></span> <span data-ttu-id="01bbc-119">有効な値は、JsonWebKeyType を参照してください。</span><span class="sxs-lookup"><span data-stu-id="01bbc-119">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="01bbc-120">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="01bbc-120">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Tags" />
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
            <span data-ttu-id="01bbc-121">取得またはキー/値ペアの形式でアプリケーション固有のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-121">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyCreateParameters.Validate " />
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
            <span data-ttu-id="01bbc-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="01bbc-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01bbc-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01bbc-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>