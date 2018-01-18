<Type Name="MicrosoftLanguageTokenizer" FullName="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer">
  <TypeSignature Language="C#" Value="public class MicrosoftLanguageTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MicrosoftLanguageTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class MicrosoftLanguageTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type MicrosoftLanguageTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MicrosoftLanguageTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="33830-101">言語固有の規則を使用してテキストを分割します。</span><span class="sxs-lookup"><span data-stu-id="33830-101">Divides text using language-specific rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.#ctor" />
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
            <span data-ttu-id="33830-102">MicrosoftLanguageTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33830-102">Initializes a new instance of the MicrosoftLanguageTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; isSearchTokenizer = null, Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; language = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; isSearchTokenizer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null, Optional isSearchTokenizer As Nullable(Of Boolean) = null, Optional language As Nullable(Of MicrosoftTokenizerLanguage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; -&gt; Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer" Usage="new Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer (name, maxTokenLength, isSearchTokenizer, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSearchTokenizer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="language" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="33830-103">トークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="33830-103">The name of the tokenizer.</span></span> <span data-ttu-id="33830-104">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="33830-104">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxTokenLength"><span data-ttu-id="33830-105">トークンの最大長。</span><span class="sxs-lookup"><span data-stu-id="33830-105">The maximum token length.</span></span> <span data-ttu-id="33830-106">トークンの最大長を超えては分割されます。</span><span class="sxs-lookup"><span data-stu-id="33830-106">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="33830-107">使用できる最大トークン長は、300 文字です。</span><span class="sxs-lookup"><span data-stu-id="33830-107">Maximum token length that can be used is 300 characters.</span></span> <span data-ttu-id="33830-108">300 文字はまず 300 の長さのトークンに分割し、これらのトークンの各分割しより長いトークンは、最大トークン長文字セットに基づいています。</span><span class="sxs-lookup"><span data-stu-id="33830-108">Tokens longer than 300 characters are first split into tokens of length 300 and then each of those tokens is split based on the max token length set.</span></span> <span data-ttu-id="33830-109">既定値は</span><span class="sxs-lookup"><span data-stu-id="33830-109">Default is</span></span>
            255.</param>
        <param name="isSearchTokenizer"><span data-ttu-id="33830-110">トークナイザの使用方法を示す値です。</span><span class="sxs-lookup"><span data-stu-id="33830-110">A value indicating how the tokenizer is used.</span></span> <span data-ttu-id="33830-111">インデックス作成のトークナイザとして使用する場合は false に設定、検索トークナイザとして使用する場合、true に設定します。</span><span class="sxs-lookup"><span data-stu-id="33830-111">Set to true if used as the search tokenizer, set to false if used as the indexing tokenizer.</span></span> <span data-ttu-id="33830-112">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="33830-112">Default is false.</span></span></param>
        <param name="language"><span data-ttu-id="33830-113">使用する言語です。</span><span class="sxs-lookup"><span data-stu-id="33830-113">The language to use.</span></span> <span data-ttu-id="33830-114">既定値は英語です。</span><span class="sxs-lookup"><span data-stu-id="33830-114">The default is English.</span></span>
            <span data-ttu-id="33830-115">使用可能な値が含まれます: 'バングラ語'、'ブルガリア語'、'カタロニア'、'chineseSimplified'、'chineseTraditional'、'クロアチア語'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フランス語の'、' ドイツ語'、'ギリシャ語'、'グジャラート語'、'ヒンディー語'、'アイスランド語'、'インドネシア語'、'イタリア語'、'日本語 '、'カンナダ語'、'韓国'、'マレー'、'マラヤーラム語'、'マラーティー語'、'norwegianBokmaal'、'ポーランド語'、'ポルトガル語-'、'portugueseBrazilian'、'パンジャブ'、'ルーマニア'、'ロシア語'、'serbianCyrillic'、'serbianLatin'、'スロベニア語'、'スペイン語'、'スウェーデン語'、'タミール語'、'テルグ'、'タイ'、'ウクライナ語'、'ウルドゥ'、'ベトナム語'</span><span class="sxs-lookup"><span data-stu-id="33830-115">Possible values include: 'bangla', 'bulgarian', 'catalan', 'chineseSimplified', 'chineseTraditional', 'croatian', 'czech', 'danish', 'dutch', 'english', 'french', 'german', 'greek', 'gujarati', 'hindi', 'icelandic', 'indonesian', 'italian', 'japanese', 'kannada', 'korean', 'malay', 'malayalam', 'marathi', 'norwegianBokmaal', 'polish', 'portuguese', 'portugueseBrazilian', 'punjabi', 'romanian', 'russian', 'serbianCyrillic', 'serbianLatin', 'slovenian', 'spanish', 'swedish', 'tamil', 'telugu', 'thai', 'ukrainian', 'urdu', 'vietnamese'</span></span></param>
        <summary>
            <span data-ttu-id="33830-116">MicrosoftLanguageTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33830-116">Initializes a new instance of the MicrosoftLanguageTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchTokenizer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSearchTokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSearchTokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.IsSearchTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchTokenizer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSearchTokenizer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.IsSearchTokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSearchTokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33830-117">取得またはトークナイザの使用方法を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="33830-117">Gets or sets a value indicating how the tokenizer is used.</span></span> <span data-ttu-id="33830-118">インデックス作成のトークナイザとして使用する場合は false に設定、検索トークナイザとして使用する場合、true に設定します。</span><span class="sxs-lookup"><span data-stu-id="33830-118">Set to true if used as the search tokenizer, set to false if used as the indexing tokenizer.</span></span> <span data-ttu-id="33830-119">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="33830-119">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As Nullable(Of MicrosoftTokenizerLanguage)" />
      <MemberSignature Language="F#" Value="member this.Language : Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Language" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="language")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33830-120">取得または使用する言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="33830-120">Gets or sets the language to use.</span></span> <span data-ttu-id="33830-121">既定値は英語です。</span><span class="sxs-lookup"><span data-stu-id="33830-121">The default is English.</span></span> <span data-ttu-id="33830-122">使用可能な値が含まれます: 'バングラ語'、'ブルガリア語'、'カタロニア'、'chineseSimplified'、'chineseTraditional'、'クロアチア語'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フランス語の'、' ドイツ語'、'ギリシャ語'、'グジャラート語'、'ヒンディー語'、'アイスランド語'、'インドネシア語'、'イタリア語'、'日本語 '、'カンナダ語'、'韓国'、'マレー'、'マラヤーラム語'、'マラーティー語'、'norwegianBokmaal'、'ポーランド語'、'ポルトガル語-'、'portugueseBrazilian'、'パンジャブ'、'ルーマニア'、'ロシア語'、'serbianCyrillic'、'serbianLatin'、'スロベニア語'、'スペイン語'、'スウェーデン語'、'タミール語'、'テルグ'、'タイ'、'ウクライナ語'、'ウルドゥ'、'ベトナム語'</span><span class="sxs-lookup"><span data-stu-id="33830-122">Possible values include: 'bangla', 'bulgarian', 'catalan', 'chineseSimplified', 'chineseTraditional', 'croatian', 'czech', 'danish', 'dutch', 'english', 'french', 'german', 'greek', 'gujarati', 'hindi', 'icelandic', 'indonesian', 'italian', 'japanese', 'kannada', 'korean', 'malay', 'malayalam', 'marathi', 'norwegianBokmaal', 'polish', 'portuguese', 'portugueseBrazilian', 'punjabi', 'romanian', 'russian', 'serbianCyrillic', 'serbianLatin', 'slovenian', 'spanish', 'swedish', 'tamil', 'telugu', 'thai', 'ukrainian', 'urdu', 'vietnamese'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.MaxTokenLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33830-123">取得または最大トークン長を設定します。</span><span class="sxs-lookup"><span data-stu-id="33830-123">Gets or sets the maximum token length.</span></span> <span data-ttu-id="33830-124">トークンの最大長を超えては分割されます。</span><span class="sxs-lookup"><span data-stu-id="33830-124">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="33830-125">使用できる最大トークン長は、300 文字です。</span><span class="sxs-lookup"><span data-stu-id="33830-125">Maximum token length that can be used is 300 characters.</span></span> <span data-ttu-id="33830-126">300 文字はまず 300 の長さのトークンに分割し、これらのトークンの各分割しより長いトークンは、最大トークン長文字セットに基づいています。</span><span class="sxs-lookup"><span data-stu-id="33830-126">Tokens longer than 300 characters are first split into tokens of length 300 and then each of those tokens is split based on the max token length set.</span></span> <span data-ttu-id="33830-127">既定値は 255 です。</span><span class="sxs-lookup"><span data-stu-id="33830-127">Default is 255.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="microsoftLanguageTokenizer.Validate " />
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
            <span data-ttu-id="33830-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="33830-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="33830-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="33830-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>