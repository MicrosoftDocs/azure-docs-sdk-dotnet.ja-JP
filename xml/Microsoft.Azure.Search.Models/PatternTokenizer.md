<Type Name="PatternTokenizer" FullName="Microsoft.Azure.Search.Models.PatternTokenizer">
  <TypeSignature Language="C#" Value="public class PatternTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type PatternTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a6ea9-101">正規表現パターンに一致する個別のトークンを構築するために使用するトークナイザ。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-101">Tokenizer that uses regex pattern matching to construct distinct tokens.</span></span> <span data-ttu-id="a6ea9-102">このトークナイザは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor" />
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
            <span data-ttu-id="a6ea9-103">PatternTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-103">Initializes a new instance of the PatternTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer (string name, string pattern = null, Microsoft.Azure.Search.Models.RegexFlags flags = null, Nullable&lt;int&gt; group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, class Microsoft.Azure.Search.Models.RegexFlags flags, valuetype System.Nullable`1&lt;int32&gt; group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor(System.String,System.String,Microsoft.Azure.Search.Models.RegexFlags,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional pattern As String = null, Optional flags As RegexFlags = null, Optional group As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternTokenizer : string * string * Microsoft.Azure.Search.Models.RegexFlags * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.PatternTokenizer" Usage="new Microsoft.Azure.Search.Models.PatternTokenizer (name, pattern, flags, group)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="flags" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="group" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a6ea9-104">トークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-104">The name of the tokenizer.</span></span> <span data-ttu-id="a6ea9-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="pattern"><span data-ttu-id="a6ea9-106">トークン区切り記号に一致する正規表現パターンです。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-106">A regular expression pattern to match token separators.</span></span> <span data-ttu-id="a6ea9-107">既定値は、1 つ以上の空白文字に一致する式です。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-107">Default is an expression that matches one or more whitespace characters.</span></span></param>
        <param name="flags"><span data-ttu-id="a6ea9-108">正規表現のフラグです。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-108">Regular expression flags.</span></span></param>
        <param name="group"><span data-ttu-id="a6ea9-109">トークンを抽出する正規表現パターンに一致するグループの 0 から始まる序数です。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-109">The zero-based ordinal of the matching group in the regular expression pattern to extract into tokens.</span></span> <span data-ttu-id="a6ea9-110">一致するグループに関係なく、トークンへの入力を分割するパターン全体を使用する場合は、-1 を使用します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-110">Use -1 if you want to use the entire pattern to split the input into tokens, irrespective of matching groups.</span></span> <span data-ttu-id="a6ea9-111">既定値は-1 です。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-111">Default is -1.</span></span></param>
        <summary>
            <span data-ttu-id="a6ea9-112">PatternTokenizer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-112">Initializes a new instance of the PatternTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RegexFlags Flags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.RegexFlags Flags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberSignature Language="VB.NET" Value="Public Property Flags As RegexFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : Microsoft.Azure.Search.Models.RegexFlags with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="flags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6ea9-113">取得または正規表現のフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-113">Gets or sets regular expression flags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Group { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberSignature Language="VB.NET" Value="Public Property Group As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Group : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="group")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6ea9-114">取得またはトークンに抽出する正規表現パターンに一致するグループの 0 から始まる序数を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-114">Gets or sets the zero-based ordinal of the matching group in the regular expression pattern to extract into tokens.</span></span> <span data-ttu-id="a6ea9-115">一致するグループに関係なく、トークンへの入力を分割するパターン全体を使用する場合は、-1 を使用します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-115">Use -1 if you want to use the entire pattern to split the input into tokens, irrespective of matching groups.</span></span> <span data-ttu-id="a6ea9-116">既定値は-1 です。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-116">Default is -1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6ea9-117">取得またはトークン区切り記号を一致させる正規表現パターンを設定します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-117">Gets or sets a regular expression pattern to match token separators.</span></span> <span data-ttu-id="a6ea9-118">既定値は、1 つ以上の空白文字に一致する式です。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-118">Default is an expression that matches one or more whitespace characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternTokenizer.Validate " />
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
            <span data-ttu-id="a6ea9-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a6ea9-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a6ea9-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>