<Type Name="DictionaryDecompounderTokenFilter" FullName="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter">
  <TypeSignature Language="C#" Value="public class DictionaryDecompounderTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DictionaryDecompounderTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class DictionaryDecompounderTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type DictionaryDecompounderTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.DictionaryDecompounderTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="381db-101">多くのゲルマン言語での複合語に分解します。</span><span class="sxs-lookup"><span data-stu-id="381db-101">Decomposes compound words found in many Germanic languages.</span></span> <span data-ttu-id="381db-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="381db-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/compound/DictionaryCompoundWordTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DictionaryDecompounderTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.#ctor" />
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
            <span data-ttu-id="381db-103">DictionaryDecompounderTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="381db-103">Initializes a new instance of the DictionaryDecompounderTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DictionaryDecompounderTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; wordList, Nullable&lt;int&gt; minWordSize = null, Nullable&lt;int&gt; minSubwordSize = null, Nullable&lt;int&gt; maxSubwordSize = null, Nullable&lt;bool&gt; onlyLongestMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; wordList, valuetype System.Nullable`1&lt;int32&gt; minWordSize, valuetype System.Nullable`1&lt;int32&gt; minSubwordSize, valuetype System.Nullable`1&lt;int32&gt; maxSubwordSize, valuetype System.Nullable`1&lt;bool&gt; onlyLongestMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, wordList As IList(Of String), Optional minWordSize As Nullable(Of Integer) = null, Optional minSubwordSize As Nullable(Of Integer) = null, Optional maxSubwordSize As Nullable(Of Integer) = null, Optional onlyLongestMatch As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter" Usage="new Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter (name, wordList, minWordSize, minSubwordSize, maxSubwordSize, onlyLongestMatch)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="wordList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="minWordSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minSubwordSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxSubwordSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="onlyLongestMatch" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="381db-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="381db-104">The name of the token filter.</span></span> <span data-ttu-id="381db-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="381db-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="wordList"><span data-ttu-id="381db-106">照合するキーワードのリスト。</span><span class="sxs-lookup"><span data-stu-id="381db-106">The list of words to match against.</span></span></param>
        <param name="minWordSize"><span data-ttu-id="381db-107">単語の最小サイズです。</span><span class="sxs-lookup"><span data-stu-id="381db-107">The minimum word size.</span></span> <span data-ttu-id="381db-108">これより長い単語がしか処理されます。</span><span class="sxs-lookup"><span data-stu-id="381db-108">Only words longer than this get processed.</span></span> <span data-ttu-id="381db-109">既定値は 5 です。</span><span class="sxs-lookup"><span data-stu-id="381db-109">Default is 5.</span></span> <span data-ttu-id="381db-110">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="381db-110">Maximum is 300.</span></span></param>
        <param name="minSubwordSize"><span data-ttu-id="381db-111">最小 subword サイズです。</span><span class="sxs-lookup"><span data-stu-id="381db-111">The minimum subword size.</span></span> <span data-ttu-id="381db-112">これより長いのみ subwords が出力されます。</span><span class="sxs-lookup"><span data-stu-id="381db-112">Only subwords longer than this are outputted.</span></span> <span data-ttu-id="381db-113">既定値は 2 です。</span><span class="sxs-lookup"><span data-stu-id="381db-113">Default is 2.</span></span> <span data-ttu-id="381db-114">最大値は</span><span class="sxs-lookup"><span data-stu-id="381db-114">Maximum is</span></span>
            300.</param>
        <param name="maxSubwordSize"><span data-ttu-id="381db-115">最大 subword サイズです。</span><span class="sxs-lookup"><span data-stu-id="381db-115">The maximum subword size.</span></span> <span data-ttu-id="381db-116">これよりも短いのみ subwords が出力されます。</span><span class="sxs-lookup"><span data-stu-id="381db-116">Only subwords shorter than this are outputted.</span></span> <span data-ttu-id="381db-117">既定値は 15 です。</span><span class="sxs-lookup"><span data-stu-id="381db-117">Default is 15.</span></span> <span data-ttu-id="381db-118">最大値は</span><span class="sxs-lookup"><span data-stu-id="381db-118">Maximum is</span></span>
            300.</param>
        <param name="onlyLongestMatch"><span data-ttu-id="381db-119">出力に一致する最長 subword のみを追加するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="381db-119">A value indicating whether to add only the longest matching subword to the output.</span></span> <span data-ttu-id="381db-120">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="381db-120">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="381db-121">DictionaryDecompounderTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="381db-121">Initializes a new instance of the DictionaryDecompounderTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSubwordSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxSubwordSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxSubwordSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MaxSubwordSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSubwordSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxSubwordSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MaxSubwordSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxSubwordSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="381db-122">取得または subword の最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="381db-122">Gets or sets the maximum subword size.</span></span> <span data-ttu-id="381db-123">これよりも短いのみ subwords が出力されます。</span><span class="sxs-lookup"><span data-stu-id="381db-123">Only subwords shorter than this are outputted.</span></span> <span data-ttu-id="381db-124">既定値は 15 です。</span><span class="sxs-lookup"><span data-stu-id="381db-124">Default is 15.</span></span> <span data-ttu-id="381db-125">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="381db-125">Maximum is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinSubwordSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinSubwordSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinSubwordSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MinSubwordSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinSubwordSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinSubwordSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MinSubwordSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minSubwordSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="381db-126">取得または subword の最小サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="381db-126">Gets or sets the minimum subword size.</span></span> <span data-ttu-id="381db-127">これより長いのみ subwords が出力されます。</span><span class="sxs-lookup"><span data-stu-id="381db-127">Only subwords longer than this are outputted.</span></span> <span data-ttu-id="381db-128">既定値は 2 です。</span><span class="sxs-lookup"><span data-stu-id="381db-128">Default is 2.</span></span> <span data-ttu-id="381db-129">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="381db-129">Maximum is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinWordSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinWordSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinWordSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MinWordSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinWordSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinWordSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.MinWordSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minWordSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="381db-130">取得または単語の最小のサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="381db-130">Gets or sets the minimum word size.</span></span> <span data-ttu-id="381db-131">これより長い単語がしか処理されます。</span><span class="sxs-lookup"><span data-stu-id="381db-131">Only words longer than this get processed.</span></span> <span data-ttu-id="381db-132">既定値は 5 です。</span><span class="sxs-lookup"><span data-stu-id="381db-132">Default is 5.</span></span> <span data-ttu-id="381db-133">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="381db-133">Maximum is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnlyLongestMatch">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OnlyLongestMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OnlyLongestMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.OnlyLongestMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property OnlyLongestMatch As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OnlyLongestMatch : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.OnlyLongestMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onlyLongestMatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="381db-134">取得または出力に一致する最長 subword のみを追加するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="381db-134">Gets or sets a value indicating whether to add only the longest matching subword to the output.</span></span> <span data-ttu-id="381db-135">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="381db-135">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dictionaryDecompounderTokenFilter.Validate " />
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
            <span data-ttu-id="381db-136">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="381db-136">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="381db-137">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="381db-137">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WordList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; WordList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; WordList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.WordList" />
      <MemberSignature Language="VB.NET" Value="Public Property WordList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.WordList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DictionaryDecompounderTokenFilter.WordList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="wordList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="381db-138">取得またはと照合するキーワードのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="381db-138">Gets or sets the list of words to match against.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>