<Type Name="KeywordTokenizerV2" FullName="Microsoft.Azure.Search.Models.KeywordTokenizerV2">
  <TypeSignature Language="C#" Value="public class KeywordTokenizerV2 : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeywordTokenizerV2 extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.KeywordTokenizerV2" />
  <TypeSignature Language="VB.NET" Value="Public Class KeywordTokenizerV2&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type KeywordTokenizerV2 = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.KeywordTokenizerV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="98f12-101">1 つのトークンとして入力全体を出力します。</span><span class="sxs-lookup"><span data-stu-id="98f12-101">Emits the entire input as a single token.</span></span> <span data-ttu-id="98f12-102">このトークナイザは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="98f12-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/KeywordTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordTokenizerV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizerV2.#ctor" />
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
            <span data-ttu-id="98f12-103">KeywordTokenizerV2 クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="98f12-103">Initializes a new instance of the KeywordTokenizerV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordTokenizerV2 (string name, Nullable&lt;int&gt; maxTokenLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizerV2.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.KeywordTokenizerV2 : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.KeywordTokenizerV2" Usage="new Microsoft.Azure.Search.Models.KeywordTokenizerV2 (name, maxTokenLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="98f12-104">トークナイザの名前。</span><span class="sxs-lookup"><span data-stu-id="98f12-104">The name of the tokenizer.</span></span> <span data-ttu-id="98f12-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="98f12-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxTokenLength"><span data-ttu-id="98f12-106">トークンの最大長。</span><span class="sxs-lookup"><span data-stu-id="98f12-106">The maximum token length.</span></span> <span data-ttu-id="98f12-107">既定値は</span><span class="sxs-lookup"><span data-stu-id="98f12-107">Default is</span></span>
            256. <span data-ttu-id="98f12-108">トークンの最大長を超えては分割されます。</span><span class="sxs-lookup"><span data-stu-id="98f12-108">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="98f12-109">使用できる最大トークン長は、300 文字です。</span><span class="sxs-lookup"><span data-stu-id="98f12-109">The maximum token length that can be used is 300 characters.</span></span></param>
        <summary>
            <span data-ttu-id="98f12-110">KeywordTokenizerV2 クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="98f12-110">Initializes a new instance of the KeywordTokenizerV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeywordTokenizerV2.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeywordTokenizerV2.MaxTokenLength" />
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
            <span data-ttu-id="98f12-111">取得または最大トークン長を設定します。</span><span class="sxs-lookup"><span data-stu-id="98f12-111">Gets or sets the maximum token length.</span></span> <span data-ttu-id="98f12-112">既定値は 256 です。</span><span class="sxs-lookup"><span data-stu-id="98f12-112">Default is 256.</span></span> <span data-ttu-id="98f12-113">トークンの最大長を超えては分割されます。</span><span class="sxs-lookup"><span data-stu-id="98f12-113">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="98f12-114">使用できる最大トークン長は、300 文字です。</span><span class="sxs-lookup"><span data-stu-id="98f12-114">The maximum token length that can be used is 300 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizerV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="keywordTokenizerV2.Validate " />
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
            <span data-ttu-id="98f12-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="98f12-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="98f12-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="98f12-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>