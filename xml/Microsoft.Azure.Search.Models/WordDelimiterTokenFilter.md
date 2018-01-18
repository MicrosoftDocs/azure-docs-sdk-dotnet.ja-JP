<Type Name="WordDelimiterTokenFilter" FullName="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter">
  <TypeSignature Language="C#" Value="public class WordDelimiterTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WordDelimiterTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class WordDelimiterTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type WordDelimiterTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.WordDelimiterTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="442bf-101">Subwords に単語を分割し、subword グループに対して省略可能な変換を実行します。</span><span class="sxs-lookup"><span data-stu-id="442bf-101">Splits words into subwords and performs optional transformations on subword groups.</span></span> <span data-ttu-id="442bf-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="442bf-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/WordDelimiterFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor" />
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
            <span data-ttu-id="442bf-103">WordDelimiterTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="442bf-103">Initializes a new instance of the WordDelimiterTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter (string name, Nullable&lt;bool&gt; generateWordParts = null, Nullable&lt;bool&gt; generateNumberParts = null, Nullable&lt;bool&gt; catenateWords = null, Nullable&lt;bool&gt; catenateNumbers = null, Nullable&lt;bool&gt; catenateAll = null, Nullable&lt;bool&gt; splitOnCaseChange = null, Nullable&lt;bool&gt; preserveOriginal = null, Nullable&lt;bool&gt; splitOnNumerics = null, Nullable&lt;bool&gt; stemEnglishPossessive = null, System.Collections.Generic.IList&lt;string&gt; protectedWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; generateWordParts, valuetype System.Nullable`1&lt;bool&gt; generateNumberParts, valuetype System.Nullable`1&lt;bool&gt; catenateWords, valuetype System.Nullable`1&lt;bool&gt; catenateNumbers, valuetype System.Nullable`1&lt;bool&gt; catenateAll, valuetype System.Nullable`1&lt;bool&gt; splitOnCaseChange, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal, valuetype System.Nullable`1&lt;bool&gt; splitOnNumerics, valuetype System.Nullable`1&lt;bool&gt; stemEnglishPossessive, class System.Collections.Generic.IList`1&lt;string&gt; protectedWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional generateWordParts As Nullable(Of Boolean) = null, Optional generateNumberParts As Nullable(Of Boolean) = null, Optional catenateWords As Nullable(Of Boolean) = null, Optional catenateNumbers As Nullable(Of Boolean) = null, Optional catenateAll As Nullable(Of Boolean) = null, Optional splitOnCaseChange As Nullable(Of Boolean) = null, Optional preserveOriginal As Nullable(Of Boolean) = null, Optional splitOnNumerics As Nullable(Of Boolean) = null, Optional stemEnglishPossessive As Nullable(Of Boolean) = null, Optional protectedWords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter : string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" Usage="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter (name, generateWordParts, generateNumberParts, catenateWords, catenateNumbers, catenateAll, splitOnCaseChange, preserveOriginal, splitOnNumerics, stemEnglishPossessive, protectedWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="generateWordParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="generateNumberParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateWords" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateNumbers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateAll" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnCaseChange" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnNumerics" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="stemEnglishPossessive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="protectedWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="442bf-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="442bf-104">The name of the token filter.</span></span> <span data-ttu-id="442bf-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="442bf-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="generateWordParts"><span data-ttu-id="442bf-106">一部の単語を生成するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-106">A value indicating whether to generate part words.</span></span> <span data-ttu-id="442bf-107">場合に生成する単語の原因の一部を設定します。たとえば"AzureSearch"では、"Azure"「検索」になります。</span><span class="sxs-lookup"><span data-stu-id="442bf-107">If set, causes parts of words to be generated; for example "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="442bf-108">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-108">Default is true.</span></span></param>
        <param name="generateNumberParts"><span data-ttu-id="442bf-109">番号 subwords を生成するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-109">A value indicating whether to generate number subwords.</span></span> <span data-ttu-id="442bf-110">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-110">Default is true.</span></span></param>
        <param name="catenateWords"><span data-ttu-id="442bf-111">Word 部分の最大の実行を catenated があるかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-111">A value indicating whether maximum runs of word parts will be catenated.</span></span> <span data-ttu-id="442bf-112">たとえば、この設定は true の場合、"Azure Search"が"AzureSearch"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-112">For example, if this is set to true, "Azure-Search" becomes "AzureSearch".</span></span> <span data-ttu-id="442bf-113">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-113">Default is false.</span></span></param>
        <param name="catenateNumbers"><span data-ttu-id="442bf-114">番号の部分の最大値が実行されるかどうかを示す値が catenated されます。</span><span class="sxs-lookup"><span data-stu-id="442bf-114">A value indicating whether maximum runs of number parts will be catenated.</span></span> <span data-ttu-id="442bf-115">たとえば、true の場合、「1-2」に設定されている場合は、「12」をなります。</span><span class="sxs-lookup"><span data-stu-id="442bf-115">For example, if this is set to true, "1-2" becomes "12".</span></span> <span data-ttu-id="442bf-116">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-116">Default is false.</span></span></param>
        <param name="catenateAll"><span data-ttu-id="442bf-117">すべての subword 部分が catenated するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-117">A value indicating whether all subword parts will be catenated.</span></span> <span data-ttu-id="442bf-118">たとえば、この設定は true の場合、「Azure-検索-1」が"AzureSearch1"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-118">For example, if this is set to true, "Azure-Search-1" becomes "AzureSearch1".</span></span> <span data-ttu-id="442bf-119">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-119">Default is false.</span></span></param>
        <param name="splitOnCaseChange"><span data-ttu-id="442bf-120">CaseChange で単語を分割するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-120">A value indicating whether to split words on caseChange.</span></span> <span data-ttu-id="442bf-121">たとえば、この設定は true の場合、"AzureSearch"が"Azure""Search"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-121">For example, if this is set to true, "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="442bf-122">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-122">Default is true.</span></span></param>
        <param name="preserveOriginal"><span data-ttu-id="442bf-123">元の単語が保持され、subword 一覧に追加するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-123">A value indicating whether original words will be preserved and added to the subword list.</span></span> <span data-ttu-id="442bf-124">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-124">Default is false.</span></span></param>
        <param name="splitOnNumerics"><span data-ttu-id="442bf-125">数値に分割するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-125">A value indicating whether to split on numbers.</span></span> <span data-ttu-id="442bf-126">たとえば、この設定は true の場合、"Azure1Search"が「1」の"Azure"「検索」です。</span><span class="sxs-lookup"><span data-stu-id="442bf-126">For example, if this is set to true, "Azure1Search" becomes "Azure" "1" "Search".</span></span> <span data-ttu-id="442bf-127">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-127">Default is true.</span></span></param>
        <param name="stemEnglishPossessive"><span data-ttu-id="442bf-128">各 subword の末尾に「の」を削除するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="442bf-128">A value indicating whether to remove trailing "'s" for each subword.</span></span> <span data-ttu-id="442bf-129">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-129">Default is true.</span></span></param>
        <param name="protectedWords"><span data-ttu-id="442bf-130">区切られたされてから保護するトークンの一覧です。</span><span class="sxs-lookup"><span data-stu-id="442bf-130">A list of tokens to protect from being delimited.</span></span></param>
        <summary>
            <span data-ttu-id="442bf-131">WordDelimiterTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="442bf-131">Initializes a new instance of the WordDelimiterTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateAll">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateAll { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateAll" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateAll As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateAll : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateAll")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-132">取得または subword のすべての部分を catenated があるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-132">Gets or sets a value indicating whether all subword parts will be catenated.</span></span> <span data-ttu-id="442bf-133">たとえば、この設定は true の場合、「Azure-検索-1」が"AzureSearch1"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-133">For example, if this is set to true, "Azure-Search-1" becomes "AzureSearch1".</span></span> <span data-ttu-id="442bf-134">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-134">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateNumbers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateNumbers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateNumbers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateNumbers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateNumbers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateNumbers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-135">取得または番号の部分の最大の実行を catenated があるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-135">Gets or sets a value indicating whether maximum runs of number parts will be catenated.</span></span> <span data-ttu-id="442bf-136">たとえば、true の場合、「1-2」に設定されている場合は、「12」をなります。</span><span class="sxs-lookup"><span data-stu-id="442bf-136">For example, if this is set to true, "1-2" becomes "12".</span></span> <span data-ttu-id="442bf-137">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-137">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-138">取得または word 部分の最大の実行を catenated があるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-138">Gets or sets a value indicating whether maximum runs of word parts will be catenated.</span></span> <span data-ttu-id="442bf-139">たとえば、この設定は true の場合、"Azure Search"が"AzureSearch"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-139">For example, if this is set to true, "Azure-Search" becomes "AzureSearch".</span></span> <span data-ttu-id="442bf-140">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-140">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateNumberParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateNumberParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateNumberParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateNumberParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateNumberParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateNumberParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-141">取得または番号 subwords を生成するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-141">Gets or sets a value indicating whether to generate number subwords.</span></span> <span data-ttu-id="442bf-142">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-142">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateWordParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateWordParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateWordParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateWordParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateWordParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateWordParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-143">取得または一部の単語を生成するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-143">Gets or sets a value indicating whether to generate part words.</span></span> <span data-ttu-id="442bf-144">場合に生成する単語の原因の一部を設定します。たとえば"AzureSearch"では、"Azure"「検索」になります。</span><span class="sxs-lookup"><span data-stu-id="442bf-144">If set, causes parts of words to be generated; for example "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="442bf-145">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-145">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-146">取得または元の単語が保持され、subword 一覧に追加するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-146">Gets or sets a value indicating whether original words will be preserved and added to the subword list.</span></span> <span data-ttu-id="442bf-147">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="442bf-147">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ProtectedWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ProtectedWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ProtectedWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-148">取得または設定されている区切りから保護するトークンの一覧。</span><span class="sxs-lookup"><span data-stu-id="442bf-148">Gets or sets a list of tokens to protect from being delimited.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnCaseChange">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnCaseChange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnCaseChange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnCaseChange As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnCaseChange : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnCaseChange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-149">取得または caseChange で単語を分割するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-149">Gets or sets a value indicating whether to split words on caseChange.</span></span> <span data-ttu-id="442bf-150">たとえば、この設定は true の場合、"AzureSearch"が"Azure""Search"です。</span><span class="sxs-lookup"><span data-stu-id="442bf-150">For example, if this is set to true, "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="442bf-151">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-151">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnNumerics">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnNumerics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnNumerics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnNumerics As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnNumerics : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnNumerics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-152">取得または数字で分割するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-152">Gets or sets a value indicating whether to split on numbers.</span></span> <span data-ttu-id="442bf-153">たとえば、この設定は true の場合、"Azure1Search"が「1」の"Azure"「検索」です。</span><span class="sxs-lookup"><span data-stu-id="442bf-153">For example, if this is set to true, "Azure1Search" becomes "Azure" "1" "Search".</span></span> <span data-ttu-id="442bf-154">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-154">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StemEnglishPossessive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StemEnglishPossessive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StemEnglishPossessive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberSignature Language="VB.NET" Value="Public Property StemEnglishPossessive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StemEnglishPossessive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stemEnglishPossessive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="442bf-155">取得または各 subword の末尾に「の」を削除するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="442bf-155">Gets or sets a value indicating whether to remove trailing "'s" for each subword.</span></span> <span data-ttu-id="442bf-156">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="442bf-156">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="wordDelimiterTokenFilter.Validate " />
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
            <span data-ttu-id="442bf-157">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="442bf-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="442bf-158">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="442bf-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>