<Type Name="CustomAnalyzer" FullName="Microsoft.Azure.Search.Models.CustomAnalyzer">
  <TypeSignature Language="C#" Value="public class CustomAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CustomAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type CustomAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CustomAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="37789-101">検索インデックス可能/トークンのテキストに変換するプロセスが細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="37789-101">Allows you to take control over the process of converting text into indexable/searchable tokens.</span></span> <span data-ttu-id="37789-102">1 つの定義済みトークナイザと 1 つまたは複数のフィルターで構成されるユーザー定義の構成することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="37789-102">It's a user-defined configuration consisting of a single predefined tokenizer and one or more filters.</span></span>
            <span data-ttu-id="37789-103">トークナイザがトークン、およびトークナイザによって生成されます。 トークンを変更するためのフィルター テキストに分割することを担当します。</span><span class="sxs-lookup"><span data-stu-id="37789-103">The tokenizer is responsible for breaking text into tokens, and the filters for modifying tokens emitted by the tokenizer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor" />
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
            <span data-ttu-id="37789-104">CustomAnalyzer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37789-104">Initializes a new instance of the CustomAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer (string name, Microsoft.Azure.Search.Models.TokenizerName tokenizer, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor(System.String,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, tokenizer As TokenizerName, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CustomAnalyzer : string * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.CustomAnalyzer" Usage="new Microsoft.Azure.Search.Models.CustomAnalyzer (name, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="37789-105">アナライザーの名前です。</span><span class="sxs-lookup"><span data-stu-id="37789-105">The name of the analyzer.</span></span> <span data-ttu-id="37789-106">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="37789-106">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="tokenizer"><span data-ttu-id="37789-107">使用して文を単語に分割することなどのトークンの一連の連続するテキストに分割するトークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="37789-107">The name of the tokenizer to use to divide continuous text into a sequence of tokens, such as breaking a sentence into words.</span></span></param>
        <param name="tokenFilters"><span data-ttu-id="37789-108">フィルターで除外または、トークナイザで生成されたトークンの変更に使用されるトークンのフィルターの一覧。</span><span class="sxs-lookup"><span data-stu-id="37789-108">A list of token filters used to filter out or modify the tokens generated by a tokenizer.</span></span> <span data-ttu-id="37789-109">たとえば、すべての文字を小文字に変換する lowercase フィルターを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="37789-109">For example, you can specify a lowercase filter that converts all characters to lowercase.</span></span> <span data-ttu-id="37789-110">フィルターはリストされている順序で実行されます。</span><span class="sxs-lookup"><span data-stu-id="37789-110">The filters are run in the order in which they are listed.</span></span></param>
        <param name="charFilters"><span data-ttu-id="37789-111">トークナイザで処理される前に、入力テキストを準備するために使用する文字フィルターの一覧。</span><span class="sxs-lookup"><span data-stu-id="37789-111">A list of character filters used to prepare input text before it is processed by the tokenizer.</span></span> <span data-ttu-id="37789-112">たとえば、特定の文字や記号が置き換えです。</span><span class="sxs-lookup"><span data-stu-id="37789-112">For instance, they can replace certain characters or symbols.</span></span> <span data-ttu-id="37789-113">フィルターはリストされている順序で実行されます。</span><span class="sxs-lookup"><span data-stu-id="37789-113">The filters are run in the order in which they are listed.</span></span></param>
        <summary>
            <span data-ttu-id="37789-114">CustomAnalyzer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37789-114">Initializes a new instance of the CustomAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="charFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37789-115">取得またはトークナイザによって処理される前に、入力テキストを準備するために使用する文字フィルターの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="37789-115">Gets or sets a list of character filters used to prepare input text before it is processed by the tokenizer.</span></span> <span data-ttu-id="37789-116">たとえば、特定の文字や記号が置き換えです。</span><span class="sxs-lookup"><span data-stu-id="37789-116">For instance, they can replace certain characters or symbols.</span></span> <span data-ttu-id="37789-117">フィルターはリストされている順序で実行されます。</span><span class="sxs-lookup"><span data-stu-id="37789-117">The filters are run in the order in which they are listed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37789-118">取得またはフィルターで除外または、トークナイザで生成されたトークンの変更に使用されるトークンのフィルターの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="37789-118">Gets or sets a list of token filters used to filter out or modify the tokens generated by a tokenizer.</span></span> <span data-ttu-id="37789-119">たとえば、すべての文字を小文字に変換する lowercase フィルターを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="37789-119">For example, you can specify a lowercase filter that converts all characters to lowercase.</span></span> <span data-ttu-id="37789-120">フィルターはリストされている順序で実行されます。</span><span class="sxs-lookup"><span data-stu-id="37789-120">The filters are run in the order in which they are listed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37789-121">取得または設定を使用して文を単語に分割することなどのトークンの一連の連続するテキストに分割するトークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="37789-121">Gets or sets the name of the tokenizer to use to divide continuous text into a sequence of tokens, such as breaking a sentence into words.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customAnalyzer.Validate " />
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
            <span data-ttu-id="37789-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="37789-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="37789-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="37789-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>