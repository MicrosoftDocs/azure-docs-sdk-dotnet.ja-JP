<Type Name="AnalyzeRequest" FullName="Microsoft.Azure.Search.Models.AnalyzeRequest">
  <TypeSignature Language="C#" Value="public class AnalyzeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AnalyzeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AnalyzeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class AnalyzeRequest" />
  <TypeSignature Language="F#" Value="type AnalyzeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="37abf-101">一部のテキストとそのテキストをトークンに分割するコンポーネントが使用される分析を指定します。</span><span class="sxs-lookup"><span data-stu-id="37abf-101">Specifies some text and analysis components used to break that text into tokens.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor" />
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
            <span data-ttu-id="37abf-102">AnalyzeRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37abf-102">Initializes a new instance of the AnalyzeRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest (string text, Microsoft.Azure.Search.Models.AnalyzerName analyzer = null, Microsoft.Azure.Search.Models.TokenizerName tokenizer = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string text, class Microsoft.Azure.Search.Models.AnalyzerName analyzer, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor(System.String,Microsoft.Azure.Search.Models.AnalyzerName,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (text As String, Optional analyzer As AnalyzerName = null, Optional tokenizer As TokenizerName = null, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AnalyzeRequest : string * Microsoft.Azure.Search.Models.AnalyzerName * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.AnalyzeRequest" Usage="new Microsoft.Azure.Search.Models.AnalyzeRequest (text, analyzer, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="analyzer" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="text"><span data-ttu-id="37abf-103">トークンに分割するテキストです。</span><span class="sxs-lookup"><span data-stu-id="37abf-103">The text to break into tokens.</span></span></param>
        <param name="analyzer"><span data-ttu-id="37abf-104">使用して、指定されたテキストを分割するアナライザーの名前。</span><span class="sxs-lookup"><span data-stu-id="37abf-104">The name of the analyzer to use to break the given text.</span></span> <span data-ttu-id="37abf-105">このパラメーターが指定されていない場合は、代わりに、トークナイザを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37abf-105">If this parameter is not specified, you must specify a tokenizer instead.</span></span> <span data-ttu-id="37abf-106">トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="37abf-106">The tokenizer and analyzer parameters are mutually exclusive.</span></span></param>
        <param name="tokenizer"><span data-ttu-id="37abf-107">使用して、指定されたテキストを分割するトークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="37abf-107">The name of the tokenizer to use to break the given text.</span></span> <span data-ttu-id="37abf-108">このパラメーターが指定されていない場合は、代わりに、アナライザーを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37abf-108">If this parameter is not specified, you must specify an analyzer instead.</span></span> <span data-ttu-id="37abf-109">トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="37abf-109">The tokenizer and analyzer parameters are mutually exclusive.</span></span></param>
        <param name="tokenFilters"><span data-ttu-id="37abf-110">指定したテキストを分割するときに使用するトークンのフィルターのオプションのリスト。</span><span class="sxs-lookup"><span data-stu-id="37abf-110">An optional list of token filters to use when breaking the given text.</span></span> <span data-ttu-id="37abf-111">このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="37abf-111">This parameter can only be set when using the tokenizer parameter.</span></span></param>
        <param name="charFilters"><span data-ttu-id="37abf-112">指定したテキストの重大なときに使用する文字のフィルターのオプションのリスト。</span><span class="sxs-lookup"><span data-stu-id="37abf-112">An optional list of character filters to use when breaking the given text.</span></span> <span data-ttu-id="37abf-113">このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="37abf-113">This parameter can only be set when using the tokenizer parameter.</span></span></param>
        <summary>
            <span data-ttu-id="37abf-114">AnalyzeRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37abf-114">Initializes a new instance of the AnalyzeRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName Analyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName Analyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.Analyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="analyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37abf-115">取得または設定を使用して、指定されたテキストを分割するアナライザーの名前。</span><span class="sxs-lookup"><span data-stu-id="37abf-115">Gets or sets the name of the analyzer to use to break the given text.</span></span> <span data-ttu-id="37abf-116">このパラメーターが指定されていない場合は、代わりに、トークナイザを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37abf-116">If this parameter is not specified, you must specify a tokenizer instead.</span></span> <span data-ttu-id="37abf-117">トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="37abf-117">The tokenizer and analyzer parameters are mutually exclusive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
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
            <span data-ttu-id="37abf-118">取得または指定されたテキストの重大なときに使用する文字のフィルターのオプションのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="37abf-118">Gets or sets an optional list of character filters to use when breaking the given text.</span></span> <span data-ttu-id="37abf-119">このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="37abf-119">This parameter can only be set when using the tokenizer parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37abf-120">取得またはトークンに分割したテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="37abf-120">Gets or sets the text to break into tokens.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
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
            <span data-ttu-id="37abf-121">取得または指定されたテキストの重大なときに使用するトークンのフィルターのオプションのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="37abf-121">Gets or sets an optional list of token filters to use when breaking the given text.</span></span> <span data-ttu-id="37abf-122">このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="37abf-122">This parameter can only be set when using the tokenizer parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
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
            <span data-ttu-id="37abf-123">取得または設定を使用して、指定されたテキストを分割するトークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="37abf-123">Gets or sets the name of the tokenizer to use to break the given text.</span></span> <span data-ttu-id="37abf-124">このパラメーターが指定されていない場合は、代わりに、アナライザーを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37abf-124">If this parameter is not specified, you must specify an analyzer instead.</span></span> <span data-ttu-id="37abf-125">トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="37abf-125">The tokenizer and analyzer parameters are mutually exclusive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="analyzeRequest.Validate " />
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
            <span data-ttu-id="37abf-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="37abf-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="37abf-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="37abf-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>