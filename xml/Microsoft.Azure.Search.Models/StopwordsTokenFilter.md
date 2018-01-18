<Type Name="StopwordsTokenFilter" FullName="Microsoft.Azure.Search.Models.StopwordsTokenFilter">
  <TypeSignature Language="C#" Value="public class StopwordsTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StopwordsTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StopwordsTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StopwordsTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StopwordsTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StopwordsTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2ef0b-101">削除は、トークンのストリームから単語を停止します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-101">Removes stop words from a token stream.</span></span> <span data-ttu-id="2ef0b-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor" />
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
            <span data-ttu-id="2ef0b-103">StopwordsTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-103">Initializes a new instance of the StopwordsTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; stopwords = null, Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList = null, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; removeTrailingStopWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; stopwords, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; removeTrailingStopWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Search.Models.StopwordsList},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional stopwords As IList(Of String) = null, Optional stopwordsList As Nullable(Of StopwordsList) = null, Optional ignoreCase As Nullable(Of Boolean) = null, Optional removeTrailingStopWords As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StopwordsTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.StopwordsTokenFilter" Usage="new Microsoft.Azure.Search.Models.StopwordsTokenFilter (name, stopwords, stopwordsList, ignoreCase, removeTrailingStopWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="stopwordsList" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="removeTrailingStopWords" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2ef0b-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-104">The name of the token filter.</span></span> <span data-ttu-id="2ef0b-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="stopwords"><span data-ttu-id="2ef0b-106">ストップ ワードの一覧です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-106">The list of stopwords.</span></span> <span data-ttu-id="2ef0b-107">このプロパティは、ストップ ワードの一覧は両方とも設定できません。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-107">This property and the stopwords list property cannot both be set.</span></span></param>
        <param name="stopwordsList"><span data-ttu-id="2ef0b-108">使用するストップ ワードの定義済みの一覧です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-108">A predefined list of stopwords to use.</span></span>
            <span data-ttu-id="2ef0b-109">このプロパティは、ストップ ワードは両方とも設定できません。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-109">This property and the stopwords property cannot both be set.</span></span>
            <span data-ttu-id="2ef0b-110">既定では英語です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-110">Default is English.</span></span> <span data-ttu-id="2ef0b-111">使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ガリシア'、'ドイツ語'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'インドネシア語'、'アイルランド語'、'イタリア語'、'ラトビア語 '、'ノルウェー語'、'ペルシャ'、'ポルトガル語-'、'ルーマニア語'、'ロシア語'、'sorani'、'スペイン'、'スウェーデン'、'タイ'、'トルコ語'</span><span class="sxs-lookup"><span data-stu-id="2ef0b-111">Possible values include: 'arabic', 'armenian', 'basque', 'brazilian', 'bulgarian', 'catalan', 'czech', 'danish', 'dutch', 'english', 'finnish', 'french', 'galician', 'german', 'greek', 'hindi', 'hungarian', 'indonesian', 'irish', 'italian', 'latvian', 'norwegian', 'persian', 'portuguese', 'romanian', 'russian', 'sorani', 'spanish', 'swedish', 'thai', 'turkish'</span></span></param>
        <param name="ignoreCase"><span data-ttu-id="2ef0b-112">大文字小文字を区別するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-112">A value indicating whether to ignore case.</span></span>
            <span data-ttu-id="2ef0b-113">True の場合、すべての単語は最初に小文字に変換されます。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-113">If true, all words are converted to lower case first.</span></span> <span data-ttu-id="2ef0b-114">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-114">Default is false.</span></span></param>
        <param name="removeTrailingStopWords"><span data-ttu-id="2ef0b-115">ストップ ワードである場合は、最後の検索用語を無視するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-115">A value indicating whether to ignore the last search term if it's a stop word.</span></span> <span data-ttu-id="2ef0b-116">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-116">Default is true.</span></span></param>
        <summary>
            <span data-ttu-id="2ef0b-117">StopwordsTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-117">Initializes a new instance of the StopwordsTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreCase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ef0b-118">取得または大文字小文字を区別するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-118">Gets or sets a value indicating whether to ignore case.</span></span> <span data-ttu-id="2ef0b-119">True の場合、すべての単語は最初に小文字に変換されます。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-119">If true, all words are converted to lower case first.</span></span> <span data-ttu-id="2ef0b-120">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-120">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveTrailingStopWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RemoveTrailingStopWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RemoveTrailingStopWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveTrailingStopWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveTrailingStopWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="removeTrailing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ef0b-121">取得または、ストップ ワードである場合は、最後の検索用語を無視するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-121">Gets or sets a value indicating whether to ignore the last search term if it's a stop word.</span></span> <span data-ttu-id="2ef0b-122">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-122">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ef0b-123">取得または、ストップ ワードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-123">Gets or sets the list of stopwords.</span></span> <span data-ttu-id="2ef0b-124">このプロパティは、ストップ ワードの一覧は両方とも設定できません。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-124">This property and the stopwords list property cannot both be set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopwordsList">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberSignature Language="VB.NET" Value="Public Property StopwordsList As Nullable(Of StopwordsList)" />
      <MemberSignature Language="F#" Value="member this.StopwordsList : Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwordsList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ef0b-125">取得または使用するストップ ワードの定義済みの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-125">Gets or sets a predefined list of stopwords to use.</span></span> <span data-ttu-id="2ef0b-126">このプロパティは、ストップ ワードは両方とも設定できません。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-126">This property and the stopwords property cannot both be set.</span></span> <span data-ttu-id="2ef0b-127">既定では英語です。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-127">Default is English.</span></span>
            <span data-ttu-id="2ef0b-128">使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ガリシア'、'ドイツ語'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'インドネシア語'、'アイルランド語'、'イタリア語'、'ラトビア語 '、'ノルウェー語'、'ペルシャ'、'ポルトガル語-'、'ルーマニア語'、'ロシア語'、'sorani'、'スペイン'、'スウェーデン'、'タイ'、'トルコ語'</span><span class="sxs-lookup"><span data-stu-id="2ef0b-128">Possible values include: 'arabic', 'armenian', 'basque', 'brazilian', 'bulgarian', 'catalan', 'czech', 'danish', 'dutch', 'english', 'finnish', 'french', 'galician', 'german', 'greek', 'hindi', 'hungarian', 'indonesian', 'irish', 'italian', 'latvian', 'norwegian', 'persian', 'portuguese', 'romanian', 'russian', 'sorani', 'spanish', 'swedish', 'thai', 'turkish'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stopwordsTokenFilter.Validate " />
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
            <span data-ttu-id="2ef0b-129">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-129">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2ef0b-130">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2ef0b-130">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>