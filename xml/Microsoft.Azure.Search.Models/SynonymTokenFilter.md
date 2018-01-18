<Type Name="SynonymTokenFilter" FullName="Microsoft.Azure.Search.Models.SynonymTokenFilter">
  <TypeSignature Language="C#" Value="public class SynonymTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynonymTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SynonymTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type SynonymTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SynonymTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ba183-101">トークン ストリームで 1 つまたは複数の単語のシノニムを一致します。</span><span class="sxs-lookup"><span data-stu-id="ba183-101">Matches single or multi-word synonyms in a token stream.</span></span> <span data-ttu-id="ba183-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="ba183-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/synonym/SynonymFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor" />
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
            <span data-ttu-id="ba183-103">SynonymTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba183-103">Initializes a new instance of the SynonymTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; synonyms, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; synonyms, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, synonyms As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null, Optional expand As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SynonymTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.SynonymTokenFilter" Usage="new Microsoft.Azure.Search.Models.SynonymTokenFilter (name, synonyms, ignoreCase, expand)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="synonyms" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="expand" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ba183-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="ba183-104">The name of the token filter.</span></span> <span data-ttu-id="ba183-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="ba183-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="synonyms"><span data-ttu-id="ba183-106">2 つの形式の次のいずれかのシノニムの一覧: 1。</span><span class="sxs-lookup"><span data-stu-id="ba183-106">A list of synonyms in following one of two formats: 1.</span></span> <span data-ttu-id="ba183-107">驚異的な多く、fabulous =&gt;驚き - の左側にあるすべての用語 =&gt;シンボルは、右側にある; 上のすべての用語に置き換えられます2 になります。</span><span class="sxs-lookup"><span data-stu-id="ba183-107">incredible, unbelievable, fabulous =&gt; amazing - all terms on the left side of =&gt; symbol will be replaced with all terms on its right side; 2.</span></span> <span data-ttu-id="ba183-108">驚異的な多く、fabulous、驚くほどの同等の単語のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="ba183-108">incredible, unbelievable, fabulous, amazing - comma separated list of equivalent words.</span></span> <span data-ttu-id="ba183-109">この一覧を解釈する方法を変更する展開オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba183-109">Set the expand option to change how this list is interpreted.</span></span></param>
        <param name="ignoreCase"><span data-ttu-id="ba183-110">示す値の照合 case-fold 入力するかどうか。</span><span class="sxs-lookup"><span data-stu-id="ba183-110">A value indicating whether to case-fold input for matching.</span></span> <span data-ttu-id="ba183-111">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="ba183-111">Default is false.</span></span></param>
        <param name="expand"><span data-ttu-id="ba183-112">すべてのシノニムの一覧で単語かどうかを示す値 (場合 =&gt;表記は使用されません) 相互にマップされます。</span><span class="sxs-lookup"><span data-stu-id="ba183-112">A value indicating whether all words in the list of synonyms (if =&gt; notation is not used) will map to one another.</span></span> <span data-ttu-id="ba183-113">シノニムの一覧で、true の場合、すべての単語 (場合 =&gt;表記は使用されません) が相互にマップします。</span><span class="sxs-lookup"><span data-stu-id="ba183-113">If true, all words in the list of synonyms (if =&gt; notation is not used) will map to one another.</span></span> <span data-ttu-id="ba183-114">次の一覧: 驚異的な多く、fabulous、優れたは等価: 驚異的な多く、fabulous、優れた =&gt;驚異的な多く、fabulous、優れたです。</span><span class="sxs-lookup"><span data-stu-id="ba183-114">The following list: incredible, unbelievable, fabulous, amazing is equivalent to: incredible, unbelievable, fabulous, amazing =&gt; incredible, unbelievable, fabulous, amazing.</span></span> <span data-ttu-id="ba183-115">False の場合、次の一覧: に同等では、fabulous、驚異的な多くの優れた: 驚異的な多く、fabulous、優れた =&gt;驚異的なです。</span><span class="sxs-lookup"><span data-stu-id="ba183-115">If false, the following list: incredible, unbelievable, fabulous, amazing will be equivalent to: incredible, unbelievable, fabulous, amazing =&gt; incredible.</span></span>
            <span data-ttu-id="ba183-116">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="ba183-116">Default is true.</span></span></param>
        <summary>
            <span data-ttu-id="ba183-117">SynonymTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba183-117">Initializes a new instance of the SynonymTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Expand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Expand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberSignature Language="VB.NET" Value="Public Property Expand As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Expand : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba183-118">取得またはすべてのシノニムの一覧で単語かどうかを示す値を設定 (場合 =&amp;gt; 表記は使用されません) が相互にマップします。</span><span class="sxs-lookup"><span data-stu-id="ba183-118">Gets or sets a value indicating whether all words in the list of synonyms (if =&amp;gt; notation is not used) will map to one another.</span></span> <span data-ttu-id="ba183-119">シノニムの一覧で、true の場合、すべての単語 (場合 =&amp;gt; 表記は使用されません) が相互にマップします。</span><span class="sxs-lookup"><span data-stu-id="ba183-119">If true, all words in the list of synonyms (if =&amp;gt; notation is not used) will map to one another.</span></span> <span data-ttu-id="ba183-120">次の一覧: 驚異的な多く、fabulous、優れたは等価: 驚異的な多く、fabulous、優れた =&amp;gt; 驚異的な多く、fabulous、優れたです。</span><span class="sxs-lookup"><span data-stu-id="ba183-120">The following list: incredible, unbelievable, fabulous, amazing is equivalent to: incredible, unbelievable, fabulous, amazing =&amp;gt; incredible, unbelievable, fabulous, amazing.</span></span> <span data-ttu-id="ba183-121">False の場合、次の一覧: に同等では、fabulous、驚異的な多くの優れた: 驚異的な多く、fabulous、優れた =&amp;gt; 驚異的なです。</span><span class="sxs-lookup"><span data-stu-id="ba183-121">If false, the following list: incredible, unbelievable, fabulous, amazing will be equivalent to: incredible, unbelievable, fabulous, amazing =&amp;gt; incredible.</span></span>
            <span data-ttu-id="ba183-122">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="ba183-122">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
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
            <span data-ttu-id="ba183-123">取得またはの照合 case-fold 入力するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba183-123">Gets or sets a value indicating whether to case-fold input for matching.</span></span> <span data-ttu-id="ba183-124">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="ba183-124">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Synonyms">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Synonyms { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Synonyms" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberSignature Language="VB.NET" Value="Public Property Synonyms As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Synonyms : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonyms")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba183-125">取得または 2 つの形式の次のいずれのシノニムの一覧を設定します。 1。</span><span class="sxs-lookup"><span data-stu-id="ba183-125">Gets or sets a list of synonyms in following one of two formats: 1.</span></span>
            <span data-ttu-id="ba183-126">驚異的な多く、fabulous =&amp;gt; すばらしい - の左側にあるすべての用語 =&amp;gt; シンボルは、右側にある; 上のすべての用語に置き換えられます2 になります。</span><span class="sxs-lookup"><span data-stu-id="ba183-126">incredible, unbelievable, fabulous =&amp;gt; amazing - all terms on the left side of =&amp;gt; symbol will be replaced with all terms on its right side; 2.</span></span> <span data-ttu-id="ba183-127">驚異的な多く、fabulous、驚くほどの同等の単語のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="ba183-127">incredible, unbelievable, fabulous, amazing - comma separated list of equivalent words.</span></span> <span data-ttu-id="ba183-128">この一覧を解釈する方法を変更する展開オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba183-128">Set the expand option to change how this list is interpreted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="synonymTokenFilter.Validate " />
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
            <span data-ttu-id="ba183-129">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ba183-129">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ba183-130">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ba183-130">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>