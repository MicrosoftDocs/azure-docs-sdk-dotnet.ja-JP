<Type Name="JsonWebKey" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKey">
  <TypeSignature Language="C#" Value="public sealed class JsonWebKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit JsonWebKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class JsonWebKey" />
  <TypeSignature Language="F#" Value="type JsonWebKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="76543-101">Http://tools.ietf.org/html/draft-ietf-jose-json-web-key-18 時点で</span><span class="sxs-lookup"><span data-stu-id="76543-101">As of http://tools.ietf.org/html/draft-ietf-jose-json-web-key-18</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConstructor</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-102"><see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="76543-102">Creates an instance of <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey (Microsoft.Azure.KeyVault.WebKey.ECParameters ecParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.WebKey.ECParameters ecParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor(Microsoft.Azure.KeyVault.WebKey.ECParameters)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey : Microsoft.Azure.KeyVault.WebKey.ECParameters -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKey" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey ecParameters" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ecParameters" Type="Microsoft.Azure.KeyVault.WebKey.ECParameters" />
      </Parameters>
      <Docs>
        <param name="ecParameters"><span data-ttu-id="76543-103">変換する EC オブジェクト</span><span class="sxs-lookup"><span data-stu-id="76543-103">The EC object to convert</span></span></param>
        <summary>
            <span data-ttu-id="76543-104">型 ec の範囲の WebKey ECParameters オブジェクトに変換します</span><span class="sxs-lookup"><span data-stu-id="76543-104">Converts a ECParameters object to a WebKey of type EC.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-105">EC オブジェクトを表す WebKey</span><span class="sxs-lookup"><span data-stu-id="76543-105">A WebKey representing the EC object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey (System.Security.Cryptography.Aes aesProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.Aes aesProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor(System.Security.Cryptography.Aes)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (aesProvider As Aes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey : System.Security.Cryptography.Aes -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKey" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey aesProvider" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="aesProvider" Type="System.Security.Cryptography.Aes" />
      </Parameters>
      <Docs>
        <param name="aesProvider"></param>
        <summary>
            <span data-ttu-id="76543-106">型のオクテットの WebKey AES オブジェクトに変換します</span><span class="sxs-lookup"><span data-stu-id="76543-106">Converts an AES object to a WebKey of type Octet</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey (System.Security.Cryptography.RSAParameters rsaParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Security.Cryptography.RSAParameters rsaParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor(System.Security.Cryptography.RSAParameters)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey : System.Security.Cryptography.RSAParameters -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKey" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey rsaParameters" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rsaParameters" Type="System.Security.Cryptography.RSAParameters" />
      </Parameters>
      <Docs>
        <param name="rsaParameters"><span data-ttu-id="76543-107">RSA オブジェクトに変換するには</span><span class="sxs-lookup"><span data-stu-id="76543-107">The RSA object to convert</span></span></param>
        <summary>
            <span data-ttu-id="76543-108">RSA 型の WebKey RSAParameters オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-108">Converts a RSAParameters object to a WebKey of type RSA.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-109">RSA オブジェクトを表す WebKey</span><span class="sxs-lookup"><span data-stu-id="76543-109">A WebKey representing the RSA object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey (System.Security.Cryptography.ECDsa ecsda, bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.ECDsa ecsda, bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor(System.Security.Cryptography.ECDsa,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ecsda As ECDsa, Optional includePrivateParameters As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey : System.Security.Cryptography.ECDsa * bool -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKey" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey (ecsda, includePrivateParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ecsda" Type="System.Security.Cryptography.ECDsa" />
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="ecsda"><span data-ttu-id="76543-110">以前に必要なキーを使用して初期化 ECDsa オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="76543-110">The ECDsa object previously initialized with the desired key.</span></span></param>
        <param name="includePrivateParameters"><span data-ttu-id="76543-111">インスタンスはならなく inclue プライベート パラメーターを説明します。</span><span class="sxs-lookup"><span data-stu-id="76543-111">Tells if the instance must inclue private parameters.</span></span>
            <span data-ttu-id="76543-112">これには、プライベート マテリアルを含めるし、エクスポート可能としてマークする ECDsa オブジェクト内のキーが必要です。</span><span class="sxs-lookup"><span data-stu-id="76543-112">This requires the key in the ECDsa object to include private material and be marked as exportable.</span></span></param>
        <summary>
            <span data-ttu-id="76543-113">ECDsa オブジェクトによって提供されるキーを持つ新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76543-113">Initializes a new instance with the key provided by the ECDsa object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonWebKey (System.Security.Cryptography.RSA rsaProvider, bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.RSA rsaProvider, bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.#ctor(System.Security.Cryptography.RSA,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rsaProvider As RSA, Optional includePrivateParameters As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey : System.Security.Cryptography.RSA * bool -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKey" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKey (rsaProvider, includePrivateParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rsaProvider" Type="System.Security.Cryptography.RSA" />
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="rsaProvider"><span data-ttu-id="76543-114">RSA オブジェクトに変換するには</span><span class="sxs-lookup"><span data-stu-id="76543-114">The RSA object to convert</span></span></param>
        <param name="includePrivateParameters"><span data-ttu-id="76543-115">RSA プライベート キー パラメーターを含める場合は true。</span><span class="sxs-lookup"><span data-stu-id="76543-115">True to include the RSA private key parameters</span></span></param>
        <summary>
            <span data-ttu-id="76543-116">RSA 型の WebKey RSA オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-116">Converts a RSA object to a WebKey of type RSA.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-117">RSA オブジェクトを表す WebKey</span><span class="sxs-lookup"><span data-stu-id="76543-117">A WebKey representing the RSA object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeRSA">
      <MemberSignature Language="C#" Value="public void CanonicalizeRSA ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CanonicalizeRSA() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.CanonicalizeRSA" />
      <MemberSignature Language="VB.NET" Value="Public Sub CanonicalizeRSA ()" />
      <MemberSignature Language="F#" Value="member this.CanonicalizeRSA : unit -&gt; unit" Usage="jsonWebKey.CanonicalizeRSA " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-118">すべての RSA パラメーターから先頭の 0 を削除します。</span><span class="sxs-lookup"><span data-stu-id="76543-118">Remove leading zeros from all RSA parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMemory">
      <MemberSignature Language="C#" Value="public void ClearMemory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ClearMemory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ClearMemory" />
      <MemberSignature Language="VB.NET" Value="Public Sub ClearMemory ()" />
      <MemberSignature Language="F#" Value="member this.ClearMemory : unit -&gt; unit" Usage="jsonWebKey.ClearMemory " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-119">最大限の努力オフ秘密キー マテリアルは、GC は、配列コンパクト中に移動するためにない strong 保証されます。</span><span class="sxs-lookup"><span data-stu-id="76543-119">Best effort to clear private key material Not strong guarantee since GC may move the arrays during compact.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurveName">
      <MemberSignature Language="C#" Value="public string CurveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.CurveName" />
      <MemberSignature Language="VB.NET" Value="Public Property CurveName As String" />
      <MemberSignature Language="F#" Value="member this.CurveName : string with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.CurveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="crv", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-120">楕円曲線暗号 (ECC) アルゴリズムの曲線</span><span class="sxs-lookup"><span data-stu-id="76543-120">The curve for Elliptic Curve Cryptography (ECC) algorithms</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="D">
      <MemberSignature Language="C#" Value="public byte[] D { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] D" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.D" />
      <MemberSignature Language="VB.NET" Value="Public Property D As Byte()" />
      <MemberSignature Language="F#" Value="member this.D : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.D" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="d", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-121">RSA プライベート指数または ECC 秘密キーです。</span><span class="sxs-lookup"><span data-stu-id="76543-121">RSA private exponent or ECC private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DP">
      <MemberSignature Language="C#" Value="public byte[] DP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] DP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.DP" />
      <MemberSignature Language="VB.NET" Value="Public Property DP As Byte()" />
      <MemberSignature Language="F#" Value="member this.DP : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.DP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="dp", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-122">RSA プライベート キーのパラメーター</span><span class="sxs-lookup"><span data-stu-id="76543-122">RSA Private Key Parameter</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DQ">
      <MemberSignature Language="C#" Value="public byte[] DQ { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] DQ" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.DQ" />
      <MemberSignature Language="VB.NET" Value="Public Property DQ As Byte()" />
      <MemberSignature Language="F#" Value="member this.DQ : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.DQ" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="dq", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-123">RSA プライベート キーのパラメーター</span><span class="sxs-lookup"><span data-stu-id="76543-123">RSA Private Key Parameter</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="E">
      <MemberSignature Language="C#" Value="public byte[] E { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] E" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.E" />
      <MemberSignature Language="VB.NET" Value="Public Property E As Byte()" />
      <MemberSignature Language="F#" Value="member this.E : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.E" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="e", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-124">RSA 公開指数、Base64 でします。</span><span class="sxs-lookup"><span data-stu-id="76543-124">RSA public exponent, in Base64.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.KeyVault.WebKey.JsonWebKey other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Equals(Microsoft.Azure.KeyVault.WebKey.JsonWebKey)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As JsonWebKey) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.KeyVault.WebKey.JsonWebKey -&gt; bool" Usage="jsonWebKey.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
      </Parameters>
      <Docs>
        <param name="other"> <span data-ttu-id="76543-125"><see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />と比較するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="76543-125">the <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> object to compare with</span></span> </param>
        <summary>
            <span data-ttu-id="76543-126">比較<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />オブジェクト</span><span class="sxs-lookup"><span data-stu-id="76543-126">Compares <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> objects</span></span>
            </summary>
        <returns> <span data-ttu-id="76543-127">かどうか、<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />オブジェクトが等しい</span><span class="sxs-lookup"><span data-stu-id="76543-127">whether the <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> objects are equals</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="jsonWebKey.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; ExtensionData;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IDictionary`2&lt;string, object&gt; ExtensionData" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public ExtensionData As IDictionary(Of String, Object) " />
      <MemberSignature Language="F#" Value="val mutable ExtensionData : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ExtensionData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-128">現在のスキーマの一部ではないプロパティを保持します。</span><span class="sxs-lookup"><span data-stu-id="76543-128">Holds properties that are not part of current schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="jsonWebKey.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPrivateKey">
      <MemberSignature Language="C#" Value="public bool HasPrivateKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool HasPrivateKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.HasPrivateKey" />
      <MemberSignature Language="VB.NET" Value="Public Function HasPrivateKey () As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPrivateKey : unit -&gt; bool" Usage="jsonWebKey.HasPrivateKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-129">このオブジェクトが、秘密キーを持つかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="76543-129">Verifies whether this object has a private key</span></span>
            </summary>
        <returns> <span data-ttu-id="76543-130">True の場合、オブジェクトに秘密キーです。false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="76543-130">True if the object has private key; false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsValid() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public Function IsValid () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : unit -&gt; bool" Usage="jsonWebKey.IsValid " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-131">WebKey オブジェクトが JsonWebKeyType の値の各規則に従った有効なかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="76543-131">Determines if the WebKey object is valid according to the rules for each of value of JsonWebKeyType.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-132">WebKey が有効な場合は true</span><span class="sxs-lookup"><span data-stu-id="76543-132">true if the WebKey is valid</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="K">
      <MemberSignature Language="C#" Value="public byte[] K { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] K" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.K" />
      <MemberSignature Language="VB.NET" Value="Public Property K As Byte()" />
      <MemberSignature Language="F#" Value="member this.K : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.K" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="k", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-133">対称キー</span><span class="sxs-lookup"><span data-stu-id="76543-133">Symmetric key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyOps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeyOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeyOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.KeyOps" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyOps As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeyOps : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.KeyOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="key_ops", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-134">サポートされているキーの操作</span><span class="sxs-lookup"><span data-stu-id="76543-134">Supported Key Operations</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kid" />
      <MemberSignature Language="VB.NET" Value="Public Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="kid", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-135">キー識別子</span><span class="sxs-lookup"><span data-stu-id="76543-135">Key Identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />
      <MemberSignature Language="VB.NET" Value="Public Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="kty", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-136">取得または Elliptic Curve、RSA HSM、オクテット、通常 RSA のサポートされている JsonWebKey キー型 (kty) を設定します。</span><span class="sxs-lookup"><span data-stu-id="76543-136">Gets or sets supported JsonWebKey key types (kty) for Elliptic Curve, RSA, HSM, Octet, usually RSA.</span></span> <span data-ttu-id="76543-137">使用可能な値が含まれます: 'EC'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="76543-137">Possible values include: 'EC', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="N">
      <MemberSignature Language="C#" Value="public byte[] N { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] N" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.N" />
      <MemberSignature Language="VB.NET" Value="Public Property N As Byte()" />
      <MemberSignature Language="F#" Value="member this.N : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.N" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="n", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-138">Base64 で RSA 剰余。</span><span class="sxs-lookup"><span data-stu-id="76543-138">RSA modulus, in Base64.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="P">
      <MemberSignature Language="C#" Value="public byte[] P { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] P" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.P" />
      <MemberSignature Language="VB.NET" Value="Public Property P As Byte()" />
      <MemberSignature Language="F#" Value="member this.P : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.P" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="p", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-139">RSA 秘密素数</span><span class="sxs-lookup"><span data-stu-id="76543-139">RSA secret prime</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Q">
      <MemberSignature Language="C#" Value="public byte[] Q { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Q" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Q" />
      <MemberSignature Language="VB.NET" Value="Public Property Q As Byte()" />
      <MemberSignature Language="F#" Value="member this.Q : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Q" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="q", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-140">P では、RSA 秘密素数&lt;q</span><span class="sxs-lookup"><span data-stu-id="76543-140">RSA secret prime, with p &lt; q</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QI">
      <MemberSignature Language="C#" Value="public byte[] QI { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] QI" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.QI" />
      <MemberSignature Language="VB.NET" Value="Public Property QI As Byte()" />
      <MemberSignature Language="F#" Value="member this.QI : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.QI" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="qi", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-141">RSA プライベート キーのパラメーター</span><span class="sxs-lookup"><span data-stu-id="76543-141">RSA Private Key Parameter</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="T">
      <MemberSignature Language="C#" Value="public byte[] T { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] T" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.T" />
      <MemberSignature Language="VB.NET" Value="Public Property T As Byte()" />
      <MemberSignature Language="F#" Value="member this.T : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.T" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="key_hsm", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-142">HSM トークン、"Bring Your Own Key"の使用</span><span class="sxs-lookup"><span data-stu-id="76543-142">HSM Token, used with "Bring Your Own Key"</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToAes">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.Aes ToAes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.Cryptography.Aes ToAes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToAes" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAes () As Aes" />
      <MemberSignature Language="F#" Value="member this.ToAes : unit -&gt; System.Security.Cryptography.Aes" Usage="jsonWebKey.ToAes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.Aes</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76543-143">型のオクテットの WebKey を AES オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-143">Converts a WebKey of type Octet to an AES object.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-144">AES オブジェクト</span><span class="sxs-lookup"><span data-stu-id="76543-144">An AES object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToECDsa">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.ECDsa ToECDsa (bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.Cryptography.ECDsa ToECDsa(bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToECDsa(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToECDsa (Optional includePrivateParameters As Boolean = false) As ECDsa" />
      <MemberSignature Language="F#" Value="member this.ToECDsa : bool -&gt; System.Security.Cryptography.ECDsa" Usage="jsonWebKey.ToECDsa includePrivateParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ECDsa</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="includePrivateParameters"><span data-ttu-id="76543-145">秘密データを含める必要があるかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76543-145">Tells if private material must be included.</span></span></param>
        <summary>
            <span data-ttu-id="76543-146">ECDsa オブジェクトを種類 EC または EC HSM の WebKey に変換します</span><span class="sxs-lookup"><span data-stu-id="76543-146">Converts a WebKey of type EC or EC-HSM to an ECDsa object</span></span>
            </summary>
        <returns><span data-ttu-id="76543-147">初期化された ECDsa インスタンス</span><span class="sxs-lookup"><span data-stu-id="76543-147">An initialized ECDsa instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEcParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.WebKey.ECParameters ToEcParameters (bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.KeyVault.WebKey.ECParameters ToEcParameters(bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToEcParameters(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEcParameters (Optional includePrivateParameters As Boolean = false) As ECParameters" />
      <MemberSignature Language="F#" Value="member this.ToEcParameters : bool -&gt; Microsoft.Azure.KeyVault.WebKey.ECParameters" Usage="jsonWebKey.ToEcParameters includePrivateParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.ECParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="includePrivateParameters"><span data-ttu-id="76543-148">秘密データを含める必要があるかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76543-148">Tells if private material must be included.</span></span></param>
        <summary>
            <span data-ttu-id="76543-149">EC または EC HSM 型 WebKey を EC パラメーター オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-149">Converts a WebKey of type EC or EC-HSM to an EC parameter object.</span></span>
            </summary>
        <returns><span data-ttu-id="76543-150">EC パラメーター オブジェクト</span><span class="sxs-lookup"><span data-stu-id="76543-150">An EC parameter object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToRSA">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.RSA ToRSA (bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.Cryptography.RSA ToRSA(bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToRSA(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToRSA (Optional includePrivateParameters As Boolean = false) As RSA" />
      <MemberSignature Language="F#" Value="member this.ToRSA : bool -&gt; System.Security.Cryptography.RSA" Usage="jsonWebKey.ToRSA includePrivateParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.RSA</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="includePrivateParameters"><span data-ttu-id="76543-151">秘密データを含める必要があるかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76543-151">Tells if private material must be included.</span></span></param>
        <summary>
            <span data-ttu-id="76543-152">RSA または RSAHSM 型 WebKey を RSA オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-152">Converts a WebKey of type RSA or RSAHSM to a RSA object</span></span>
            </summary>
        <returns><span data-ttu-id="76543-153">初期化された RSA インスタンス</span><span class="sxs-lookup"><span data-stu-id="76543-153">An initialized RSA instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToRSAParameters">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.RSAParameters ToRSAParameters (bool includePrivateParameters = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Security.Cryptography.RSAParameters ToRSAParameters(bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToRSAParameters(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToRSAParameters (Optional includePrivateParameters As Boolean = false) As RSAParameters" />
      <MemberSignature Language="F#" Value="member this.ToRSAParameters : bool -&gt; System.Security.Cryptography.RSAParameters" Usage="jsonWebKey.ToRSAParameters includePrivateParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.RSAParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="includePrivateParameters"><span data-ttu-id="76543-154">秘密データを含める必要があるかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76543-154">Tells if private material must be included.</span></span></param>
        <summary>
            <span data-ttu-id="76543-155">RSA または RSAHSM 型 WebKey を RSA パラメーター オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="76543-155">Converts a WebKey of type RSA or RSAHSM to a RSA parameter object</span></span>
            </summary>
        <returns><span data-ttu-id="76543-156">RSA パラメーター</span><span class="sxs-lookup"><span data-stu-id="76543-156">An RSA parameter</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jsonWebKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VisitProperties">
      <MemberSignature Language="C#" Value="public void VisitProperties (Action&lt;string,object&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void VisitProperties(class System.Action`2&lt;string, object&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.VisitProperties(System.Action{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub VisitProperties (visitor As Action(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.VisitProperties : Action&lt;string, obj&gt; -&gt; unit" Usage="jsonWebKey.VisitProperties visitor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visitor" Type="System.Action&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="visitor"><span data-ttu-id="76543-157">プロパティごとに呼び出される訪問者。</span><span class="sxs-lookup"><span data-stu-id="76543-157">A visitor that will be called for each property.</span></span></param>
        <summary>
            <span data-ttu-id="76543-158">指定された訪問者を呼び出して、このオブジェクトのすべての JSON のプロパティを反復処理します。</span><span class="sxs-lookup"><span data-stu-id="76543-158">Iterates over all JSON properties of this object, calling the specified visitor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="X">
      <MemberSignature Language="C#" Value="public byte[] X { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] X" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.X" />
      <MemberSignature Language="VB.NET" Value="Public Property X As Byte()" />
      <MemberSignature Language="F#" Value="member this.X : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.X" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="x", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-159">楕円曲線の X 座標をポイントします。</span><span class="sxs-lookup"><span data-stu-id="76543-159">X coordinate for the Elliptic Curve point.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Y">
      <MemberSignature Language="C#" Value="public byte[] Y { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Y" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Y" />
      <MemberSignature Language="VB.NET" Value="Public Property Y As Byte()" />
      <MemberSignature Language="F#" Value="member this.Y : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Y" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.KeyVault.WebKey.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="y", Required=Newtonsoft.Json.Required.Default)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76543-160">楕円曲線ポイントの Y 座標。</span><span class="sxs-lookup"><span data-stu-id="76543-160">Y coordinate for the Elliptic Curve point.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>