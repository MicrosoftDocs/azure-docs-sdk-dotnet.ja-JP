<Type Name="TokenizerName" FullName="Microsoft.Azure.Search.Models.TokenizerName">
  <TypeSignature Language="C#" Value="public sealed class TokenizerName : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenizerName extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.TokenizerName&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenizerName" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenizerName&#xA;Inherits ExtensibleEnum(Of TokenizerName)" />
  <TypeSignature Language="F#" Value="type TokenizerName = class&#xA;    inherit ExtensibleEnum&lt;TokenizerName&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.TokenizerName</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f33b1-101">Azure Search でサポートされているすべてのサロゲートの名前を定義します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-101">Defines the names of all tokenizers supported by Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Classic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Classic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Classic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Classic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Classic As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Classic : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Classic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-102">ほとんどのヨーロッパ言語のドキュメントを処理するために適切な文法ベース トークナイザ。</span><span class="sxs-lookup"><span data-stu-id="f33b1-102">Grammar-based tokenizer that is suitable for processing most European-language documents.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/ClassicTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.TokenizerName Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.TokenizerName Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenizerName.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As TokenizerName" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f33b1-103">トークナイザの名前です。</span><span class="sxs-lookup"><span data-stu-id="f33b1-103">Name of the tokenizer.</span></span></param>
        <summary>
            <span data-ttu-id="f33b1-104">TokenizerName インスタンスの新規作成または既知のトークナイザの指定した名前に一致する場合に、既存のインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-104">Creates a new TokenizerName instance, or returns an existing instance if the given name matches that of a known tokenizer.</span></span>
            </summary>
        <returns><span data-ttu-id="f33b1-105">指定した名前の TokenizerName インスタンス。</span><span class="sxs-lookup"><span data-stu-id="f33b1-105">A TokenizerName instance with the given name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName EdgeNGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName EdgeNGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.EdgeNGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EdgeNGram As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable EdgeNGram : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.EdgeNGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-106">指定されたサイズの n-gram のエッジからの入力をトークン化です。</span><span class="sxs-lookup"><span data-stu-id="f33b1-106">Tokenizes the input from an edge into n-grams of the given size(s).</span></span>
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keyword">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Keyword;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Keyword" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Keyword" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Keyword As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Keyword : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Keyword" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-107">1 つのトークンとして入力全体を出力します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-107">Emits the entire input as a single token.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/KeywordTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Letter">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Letter;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Letter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Letter" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Letter As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Letter : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Letter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-108">英字以外でテキストを分割します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-108">Divides text at non-letters.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LetterTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lowercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Lowercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Lowercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Lowercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Lowercase As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Lowercase : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Lowercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-109">英字以外でテキストを分割し、それらを小文字に変換します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-109">Divides text at non-letters and converts them to lower case.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LowerCaseTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftLanguageStemmingTokenizer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageStemmingTokenizer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageStemmingTokenizer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageStemmingTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MicrosoftLanguageStemmingTokenizer As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable MicrosoftLanguageStemmingTokenizer : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageStemmingTokenizer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-110">言語固有の規則を使用してテキストを分割し、基本フォームに単語を短縮します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-110">Divides text using language-specific rules and reduces words to their base forms.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftLanguageTokenizer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageTokenizer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageTokenizer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MicrosoftLanguageTokenizer As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable MicrosoftLanguageTokenizer : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageTokenizer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-111">言語固有の規則を使用してテキストを分割します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-111">Divides text using language-specific rules.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName NGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName NGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.NGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NGram As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable NGram : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.NGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-112">指定されたサイズの n-gram への入力をトークン化です。</span><span class="sxs-lookup"><span data-stu-id="f33b1-112">Tokenizes the input into n-grams of the given size(s).</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.TokenizerName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.TokenizerName op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenizerName.op_Implicit(System.String)~Microsoft.Azure.Search.Models.TokenizerName" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As TokenizerName" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f33b1-113">変換する文字列。</span><span class="sxs-lookup"><span data-stu-id="f33b1-113">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="f33b1-114">文字列から TokenizerName への暗黙的な変換を定義します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-114">Defines implicit conversion from string to TokenizerName.</span></span>
            </summary>
        <returns><span data-ttu-id="f33b1-115">TokenizerName として文字列です。</span><span class="sxs-lookup"><span data-stu-id="f33b1-115">The string as a TokenizerName.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathHierarchy">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName PathHierarchy;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName PathHierarchy" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.PathHierarchy" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PathHierarchy As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable PathHierarchy : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.PathHierarchy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-116">パスのような階層のトークナイザ。</span><span class="sxs-lookup"><span data-stu-id="f33b1-116">Tokenizer for path-like hierarchies.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/path/PathHierarchyTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Pattern;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Pattern" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Pattern As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Pattern : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Pattern" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-117">正規表現パターンに一致する個別のトークンを構築するために使用するトークナイザ。</span><span class="sxs-lookup"><span data-stu-id="f33b1-117">Tokenizer that uses regex pattern matching to construct distinct tokens.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Standard">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Standard;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Standard" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Standard" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Standard As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Standard : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Standard" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-118">標準 Lucene アナライザーです。標準トークナイザー、小文字のフィルターおよびフィルターで構成されます。</span><span class="sxs-lookup"><span data-stu-id="f33b1-118">Standard Lucene analyzer; Composed of the standard tokenizer, lowercase filter and stop filter.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/StandardTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UaxUrlEmail">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName UaxUrlEmail;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName UaxUrlEmail" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.UaxUrlEmail" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UaxUrlEmail As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable UaxUrlEmail : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.UaxUrlEmail" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-119">Url と電子メールを 1 つのトークンとしてトークン化です。</span><span class="sxs-lookup"><span data-stu-id="f33b1-119">Tokenizes urls and emails as one token.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/UAX29URLEmailTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Whitespace">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Whitespace;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Whitespace" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Whitespace" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Whitespace As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Whitespace : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Whitespace" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f33b1-120">空白文字でテキストを分割します。</span><span class="sxs-lookup"><span data-stu-id="f33b1-120">Divides text at whitespace.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/WhitespaceTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>