<Type Name="PhoneticTokenFilter" FullName="Microsoft.Azure.Search.Models.PhoneticTokenFilter">
  <TypeSignature Language="C#" Value="public class PhoneticTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PhoneticTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PhoneticTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PhoneticTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PhoneticTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PhoneticTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1ed5e-101">ルビの一致のトークンを作成します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-101">Create tokens for phonetic matches.</span></span> <span data-ttu-id="1ed5e-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-phonetic/org/apache/lucene/analysis/phonetic/package-tree.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ed5e-103">PhoneticTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-103">Initializes a new instance of the PhoneticTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter (string name, Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder = null, Nullable&lt;bool&gt; replaceOriginalTokens = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder, valuetype System.Nullable`1&lt;bool&gt; replaceOriginalTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor(System.String,System.Nullable{Microsoft.Azure.Search.Models.PhoneticEncoder},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional encoder As Nullable(Of PhoneticEncoder) = null, Optional replaceOriginalTokens As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PhoneticTokenFilter : string * Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.PhoneticTokenFilter" Usage="new Microsoft.Azure.Search.Models.PhoneticTokenFilter (name, encoder, replaceOriginalTokens)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="encoder" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;" />
        <Parameter Name="replaceOriginalTokens" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="1ed5e-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-104">The name of the token filter.</span></span> <span data-ttu-id="1ed5e-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="encoder"><span data-ttu-id="1ed5e-106">使用する音声のエンコーダー。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-106">The phonetic encoder to use.</span></span> <span data-ttu-id="1ed5e-107">既定値は、"metaphone"です。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-107">Default is "metaphone".</span></span> <span data-ttu-id="1ed5e-108">使用可能な値が含まれます: 'metaphone'、'doubleMetaphone'、'soundex'、'refinedSoundex'、'caverphone1'、'caverphone2'、'ケルン'、'nysiis'、'koelnerPhonetik'、'haasePhonetik'、'beiderMorse'</span><span class="sxs-lookup"><span data-stu-id="1ed5e-108">Possible values include: 'metaphone', 'doubleMetaphone', 'soundex', 'refinedSoundex', 'caverphone1', 'caverphone2', 'cologne', 'nysiis', 'koelnerPhonetik', 'haasePhonetik', 'beiderMorse'</span></span></param>
        <param name="replaceOriginalTokens"><span data-ttu-id="1ed5e-109">エンコードされたトークンが元のトークンを置き換える必要があるかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-109">A value indicating whether encoded tokens should replace original tokens.</span></span> <span data-ttu-id="1ed5e-110">False の場合、エンコードされたトークンがシノニムとして追加されます。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-110">If false, encoded tokens are added as synonyms.</span></span> <span data-ttu-id="1ed5e-111">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-111">Default is true.</span></span></param>
        <summary>
            <span data-ttu-id="1ed5e-112">PhoneticTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-112">Initializes a new instance of the PhoneticTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoder">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoder As Nullable(Of PhoneticEncoder)" />
      <MemberSignature Language="F#" Value="member this.Encoder : Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoder")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed5e-113">取得または使用する音声のエンコーダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-113">Gets or sets the phonetic encoder to use.</span></span> <span data-ttu-id="1ed5e-114">既定値は、"metaphone"です。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-114">Default is "metaphone".</span></span>
            <span data-ttu-id="1ed5e-115">使用可能な値が含まれます: 'metaphone'、'doubleMetaphone'、'soundex'、'refinedSoundex'、'caverphone1'、'caverphone2'、'ケルン'、'nysiis'、'koelnerPhonetik'、'haasePhonetik'、'beiderMorse'</span><span class="sxs-lookup"><span data-stu-id="1ed5e-115">Possible values include: 'metaphone', 'doubleMetaphone', 'soundex', 'refinedSoundex', 'caverphone1', 'caverphone2', 'cologne', 'nysiis', 'koelnerPhonetik', 'haasePhonetik', 'beiderMorse'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceOriginalTokens">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReplaceOriginalTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReplaceOriginalTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplaceOriginalTokens As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReplaceOriginalTokens : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ed5e-116">取得またはエンコードされたトークンが元のトークンを置き換える必要があるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-116">Gets or sets a value indicating whether encoded tokens should replace original tokens.</span></span> <span data-ttu-id="1ed5e-117">False の場合、エンコードされたトークンがシノニムとして追加されます。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-117">If false, encoded tokens are added as synonyms.</span></span> <span data-ttu-id="1ed5e-118">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-118">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="phoneticTokenFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ed5e-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1ed5e-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1ed5e-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>