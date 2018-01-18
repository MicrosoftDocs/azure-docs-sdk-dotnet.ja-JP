<Type Name="EdgeNGramTokenizer" FullName="Microsoft.Azure.Search.Models.EdgeNGramTokenizer">
  <TypeSignature Language="C#" Value="public class EdgeNGramTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EdgeNGramTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.EdgeNGramTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class EdgeNGramTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type EdgeNGramTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.EdgeNGramTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a5fcc-101">指定されたサイズの n-gram のエッジからの入力をトークン化です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-101">Tokenizes the input from an edge into n-grams of the given size(s).</span></span>
            <span data-ttu-id="a5fcc-102">このトークナイザは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EdgeNGramTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.#ctor" />
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
            <span data-ttu-id="a5fcc-103">EdgeNGramTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-103">Initializes a new instance of the EdgeNGramTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EdgeNGramTokenizer (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; tokenChars = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.TokenCharacterKind&gt; tokenChars) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenCharacterKind})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null, Optional tokenChars As IList(Of TokenCharacterKind) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.EdgeNGramTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; -&gt; Microsoft.Azure.Search.Models.EdgeNGramTokenizer" Usage="new Microsoft.Azure.Search.Models.EdgeNGramTokenizer (name, minGram, maxGram, tokenChars)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="tokenChars" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a5fcc-104">トークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-104">The name of the tokenizer.</span></span> <span data-ttu-id="a5fcc-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="minGram"><span data-ttu-id="a5fcc-106">最小 n グラム長。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-106">The minimum n-gram length.</span></span> <span data-ttu-id="a5fcc-107">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-107">Default is 1.</span></span>
            <span data-ttu-id="a5fcc-108">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-108">Maximum is 300.</span></span> <span data-ttu-id="a5fcc-109">MaxGram の値よりも小さい必要があります。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-109">Must be less than the value of maxGram.</span></span></param>
        <param name="maxGram"><span data-ttu-id="a5fcc-110">N グラムの最大長。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-110">The maximum n-gram length.</span></span> <span data-ttu-id="a5fcc-111">既定値は 2 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-111">Default is 2.</span></span>
            <span data-ttu-id="a5fcc-112">最大値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-112">Maximum is 300.</span></span></param>
        <param name="tokenChars"><span data-ttu-id="a5fcc-113">文字クラス トークン内に維持します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-113">Character classes to keep in the tokens.</span></span></param>
        <summary>
            <span data-ttu-id="a5fcc-114">EdgeNGramTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-114">Initializes a new instance of the EdgeNGramTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenizer.MaxGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5fcc-115">取得または n グラムの最大の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-115">Gets or sets the maximum n-gram length.</span></span> <span data-ttu-id="a5fcc-116">既定値は 2 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-116">Default is 2.</span></span> <span data-ttu-id="a5fcc-117">最大値は</span><span class="sxs-lookup"><span data-stu-id="a5fcc-117">Maximum is</span></span>
            300.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenizer.MinGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5fcc-118">取得または n グラムの最小の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-118">Gets or sets the minimum n-gram length.</span></span> <span data-ttu-id="a5fcc-119">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-119">Default is 1.</span></span> <span data-ttu-id="a5fcc-120">最大値は</span><span class="sxs-lookup"><span data-stu-id="a5fcc-120">Maximum is</span></span>
            300. <span data-ttu-id="a5fcc-121">MaxGram の値よりも小さい必要があります。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-121">Must be less than the value of maxGram.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenChars">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; TokenChars { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.TokenCharacterKind&gt; TokenChars" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.TokenChars" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenChars As IList(Of TokenCharacterKind)" />
      <MemberSignature Language="F#" Value="member this.TokenChars : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenizer.TokenChars" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenChars")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5fcc-122">取得またはトークンに保持する文字クラスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-122">Gets or sets character classes to keep in the tokens.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="edgeNGramTokenizer.Validate " />
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
            <span data-ttu-id="a5fcc-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a5fcc-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a5fcc-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>